# RAG-Based PDF Chatbot (No API)

End-to-end GenAI project demonstrating Retrieval-Augmented Generation (RAG) without external APIs.

---

## Problem Statement
Traditional search systems rely on keyword matching and fail to understand context.  
This project solves it using semantic search + LLM to generate meaningful answers from documents.

---

## Key Highlights
- Semantic search using embeddings (MiniLM)
- FAISS vector database for fast retrieval
- Local LLM (GPT-2) — no API required
- Works on custom PDF documents

---

## Workflow
1. Load PDF  
2. Split text into chunks  
3. Convert text into embeddings  
4. Store embeddings in FAISS  
5. Retrieve relevant chunks  
6. Generate answer using LLM  

---

## 📸 Output Example

Below is a sample output from the RAG system:

![RAG Chatbot Output](./output.png)
