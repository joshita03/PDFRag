# 🧠 pdfRAG – Ask Questions from Your PDFs with LLMs

**pdfRAG** is a Retrieval-Augmented Generation (RAG) pipeline that lets you ask natural language questions from your PDF documents. It uses local LLMs (like LLaMA 2 via Ollama), vector databases (FAISS, ChromaDB, Qdrant), and semantic embeddings (DocArray) to give you grounded, contextual responses.

---

## 🚀 Features

- 📄 Ingest and process multiple PDFs
- 🔎 Chunk and embed text using **DocArray**
- 💾 Store vectors in **ChromaDB**, **FAISS**, or **Qdrant**
- 🧠 Query with **LLaMA 2** via **Ollama**
- 🔗 Built using **LangChain** modules
- 💬 Get answers based on the actual content inside your PDFs

---

## 🧱 Tech Stack

- **LangChain**
- **Ollama (LLaMA 2)**
- **ChromaDB / FAISS / Qdrant**
- **DocArray**
- **PyPDF**
- `os`, `itemgetter` (Python built-ins)
