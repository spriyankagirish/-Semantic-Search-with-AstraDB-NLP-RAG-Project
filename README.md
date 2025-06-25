

# Semantic Search with AstraDB | NLP & RAG Project

📂 **Skills Highlighted:** NLP · RAG · Vector Databases · MMR · Prompt Engineering · LLMs

---

## 📘 Project Overview

This project demonstrates a complete **semantic search pipeline** using **Retrieval-Augmented Generation (RAG)**. It integrates **AstraDB** for vector storage, uses **Maximal Marginal Relevance (MMR)** for reranking, and applies **LLMs** to generate accurate, context-aware responses from unstructured PDF content.

---

## 🔧 Tech Stack & Tools

* 🐍 **Python**
* 🔗 **LangChain**
* 🗃 **AstraDB Vector Store** (via **CassIO**)
* 🧠 **LLMs** (OpenAI, Gemini via LangChain)
* 🧬 **Sentence Transformers** (HuggingFace)
* 📊 **MMR Retrieval** (via LangChain retrievers)

---

## 🔁 Pipeline Overview

```
PDF 📄  
   ↓  
Chunking ✂️ (Semantic-based)  
   ↓  
Embedding 🧬 (Sentence Transformers)  
   ↓  
AstraDB 🗃 (Vector Store with CassIO)  
   ↓  
MMR Retrieval 🪄 (Maximal Marginal Relevance)  
   ↓  
RetrievalQA Chain 🔍 (LangChain-based pipeline)  
   ↓  
Manual Prompting with LLM 🧠  
   ↓  
Final Output: Displayed Answer ✅
```

---

## 🧩 Key Pipeline Components

| Step                  | Description                                                                |
| --------------------- | -------------------------------------------------------------------------- |
| 📄 **PDF Ingestion**  | Extracts content from multi-page PDF files                                 |
| ✂️ **Chunking**       | Splits text into semantically meaningful chunks                            |
| 🧬 **Embedding**      | Converts chunks into dense vectors using `sentence-transformers`           |
| 🗃 **Vector Storage** | Stores embeddings and metadata in AstraDB with CassIO                      |
| 🪄 **MMR Retrieval**  | Retrieves diverse and relevant chunks using Maximal Marginal Relevance     |
| 🔍 **RetrievalQA**    | Combines retriever and LLM to generate context-rich answers                |
| 🧠 **LLM Prompting**  | Custom manual prompts crafted for specific, high-quality LLM responses     |
| ✅ **Output Display**  | Final response is printed/displayed to the user based on retrieved context |

---

## 📌 Highlights & Capabilities

* ✅ **End-to-end RAG pipeline** from raw documents to LLM-based answers
* ✅ **Semantic chunking** for improved context and relevance
* ✅ **AstraDB + CassIO integration** for efficient vector search
* ✅ **MMR reranking** for balanced, diverse retrieval
* ✅ **RetrievalQA and Prompt Engineering** for high-quality answers


