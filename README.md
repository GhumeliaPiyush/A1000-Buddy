# 🤖 A1000 Buddy

**A1000 Buddy** is an AI-powered chatbot for the **Yaskawa A1000** drive.  
It helps technicians and engineers by answering questions about:

- Drive parameters (codes, ranges, defaults, descriptions)  
- Fault codes and remedies  
- Installation guidelines  

Built with **LLM + Retrieval-Augmented Generation (RAG)** for accurate, context-grounded answers.

---

## 🚀 Features
- Query A1000 manual in natural language  
- Semantic search using embeddings + FAISS  
- AI-generated answers grounded in documentation  
- Modular design: CLI → GUI → API → Web  
- Easily extendable to other drive models  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- [pdfplumber](https://github.com/jsvine/pdfplumber) – extract text from manuals  
- [sentence-transformers](https://www.sbert.net/) – embeddings  
- [FAISS](https://github.com/facebookresearch/faiss) – vector search  
- [OpenAI](https://openai.com/) or local LLM – answer generation  
- [PySide6](https://doc.qt.io/qtforpython/) – GUI (future)  

---

## 📂 Project Structure
