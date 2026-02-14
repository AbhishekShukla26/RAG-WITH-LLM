# 🔎 RAG Pipeline with LLM using Hugging Face & FAISS

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG) pipeline** using Python, Hugging Face Transformers, Sentence Transformers, FAISS, and Wikipedia as an external knowledge source.

Large Language Models (LLMs) are powerful but have a key limitation — their knowledge is static and limited to training data. RAG solves this by retrieving relevant external information before generating responses.

---

## 🚀 What is RAG?

Retrieval-Augmented Generation (RAG) consists of two main components:

### 🔹 Retriever
Searches a knowledge base to find relevant documents based on the user's query.

### 🔹 Generator
Uses retrieved documents as context to generate accurate and meaningful responses.

---

## 🎯 Key Benefits of RAG

- Reduces hallucinations in LLM responses  
- Provides up-to-date knowledge without retraining  
- Improves factual accuracy  
- Enables context-aware AI responses  

---

## 🏗️ Project Workflow

This project follows these steps:

1. Retrieve Wikipedia content based on a topic
2. Split text into smaller chunks
3. Convert text chunks into embeddings
4. Store embeddings using FAISS vector index
5. Retrieve relevant chunks for a query
6. Use an LLM QA model to generate answers

---

## ⚙️ Tech Stack

- Python
- Hugging Face Transformers
- Sentence Transformers
- FAISS (Vector Search)
- Wikipedia API
- NumPy

---

## 📦 Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/AbhishekShukla26/RAG-WITH-LLM.git
cd RAG-WITH-LLM
