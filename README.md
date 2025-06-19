# 🔍 Semantic Search with FAISS

This project demonstrates how to build a semantic search engine using:
- Hugging Face `transformers` for generating embeddings
- `datasets` library for preprocessing
- `faiss-cpu` for fast similarity search

It indexes GitHub issues (including their titles, bodies, and comments) and allows querying with natural language to retrieve the most relevant discussion threads.

---

## 🚀 Features

- Load and filter GitHub issue threads from Hugging Face Hub
- Generate dense vector embeddings using the `multi-qa-mpnet-base-dot-v1` model
- Build a FAISS index from the embeddings
- Perform semantic search to retrieve top relevant issue comments

---
