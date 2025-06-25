# Semantic-Search-with-AstraDB-NLP-RAG-Project
📂 Skills Highlighted: NLP · RAG · Vector Databases · MMR · Prompt Engineering · LLMs

📘 Project Overview
This project demonstrates a complete semantic search pipeline using Retrieval-Augmented Generation (RAG). It combines AstraDB for vector storage, Maximal Marginal Relevance (MMR) for reranking, and LLMs for generating accurate, context-aware responses.

🔧 Tech Stack & Tools
Python

LangChain

AstraDB (Vector Store) + CassIO

Sentence Transformers (HuggingFace)

MMR Reranking (via LangChain retrievers)

LLMs (e.g., OpenAI, Gemini via LangChain)

🔁 Pipeline Overview
scss
Copy
Edit
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
🧩 Key Pipeline Components
Step	Description
📄 PDF Ingestion	Extracts content from multi-page PDF files
✂️ Chunking	Splits text into semantically meaningful chunks
🧬 Embedding	Converts chunks to vector form using sentence-transformers
🗃 Vector Storage	Stores vectors and metadata in AstraDB with CassIO
🪄 MMR Retrieval	Uses Maximal Marginal Relevance for better diversity
🔍 RetrievalQA	Combines retriever and LLM to generate context-aware answers
🧠 LLM Prompting	Manual prompt templates used to guide response generation
✅ Output	Final answer displayed based on retrieved context

📌 Highlights & Capabilities
✅ Full RAG workflow from PDF to intelligent answer
✅ Semantic chunking for better retrieval accuracy
✅ AstraDB integration for scalable vector search
✅ Maximal Marginal Relevance (MMR) improves diversity
✅ RetrievalQA & LLM prompting for accurate responses

💡 This project showcases how to combine vector databases, semantic embeddings, and large language models to build intelligent document search and question-answering systems.
