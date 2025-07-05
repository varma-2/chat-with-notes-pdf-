# 📄 PDF Question Answering System using RAG

This project implements a **PDF-based Question Answering system** using **Retrieval-Augmented Generation (RAG)**. Users can securely upload PDF files and ask questions in natural language. The system extracts relevant content from the PDFs and returns answers based on semantic similarity.

---

## 🚀 Features

- 🔐 **User Authentication** (JWT-based)
- 📤 **PDF Upload** with metadata storage
- 📄 **Text Extraction** from uploaded PDFs using PyMuPDF
- 🔍 **Semantic Search** using SentenceTransformers and FAISS
- 🤖 **Question Answering** via context retrieval from PDF
- 📡 **Node.js + Python Integration** for efficient pipeline execution

---

## 🛠️ Tech Stack

**Backend:**
- Node.js with Express
- MongoDB (via Mongoose)
- JWT Authentication
- Express File Upload

**Python (RAG Pipeline):**
- PyMuPDF (fitz)
- SentenceTransformers
- FAISS for similarity search
- Argparse for CLI integration

---



