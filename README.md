# RAG_from_scratch

An end-to-end **Retrieval-Augmented Generation (RAG)** system built from scratch using open-source tools.  
This project enables a language model to answer questions **only using provided documents**, significantly reducing hallucinations.

---

## 🚀 What This Project Does

- Ingests raw text documents
- Splits them into overlapping chunks
- Converts chunks into semantic embeddings
- Stores embeddings in a vector database
- Retrieves the most relevant chunks for a query
- Augments the LLM prompt with retrieved context
- Generates grounded answers using a transformer-based model

---

## 🧠 Why RAG?

Traditional language models rely solely on training data and may hallucinate or provide outdated information.  
RAG solves this by **retrieving real documents at query time** and forcing the model to answer based on them.

---

## 🏗️ Architecture Overview

User Question  
→ Embedding  
→ Vector Search (ChromaDB)  
→ Relevant Document Chunks  
→ Prompt Augmentation  
→ Language Model  
→ Grounded Answer

---

## 🧩 Tech Stack (100% Free)

| Component | Tool |
|--------|------|
| Embeddings | SentenceTransformers (all-MiniLM-L6-v2) |
| Vector Database | ChromaDB |
| Language Model | google/flan-t5-small |
| Platform | Google Colab |
| Language | Python |

---

## 📂 Project Structure


