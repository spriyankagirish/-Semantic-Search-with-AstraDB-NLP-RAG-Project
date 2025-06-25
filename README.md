# -Semantic-Search-with-AstraDB-NLP-RAG-Project

📂 Skills Highlighted: NLP · RAG · Vector Databases · BM25 · Prompt Engineering · LLMs

📘 Project Overview
This project showcases a complete semantic search pipeline powered by Retrieval-Augmented Generation (RAG). It leverages AstraDB as a vector store, integrates BM25/MMR reranking, and utilizes LLMs to generate context-aware responses — with the final output rendered into a professional DOCX report.

🔧 Tech Stack & Tools
Python

LangChain

AstraDB (Vector Store) + CassIO

Sentence Transformers (HuggingFace)

BM25 & MMR Reranking

LLMs (e.g., OpenAI/Gemini via LangChain)

python-docx for Report Generation

🧩 Key Pipeline Components
Step	Description
📄 PDF Ingestion	Parse and extract content from multi-page PDFs
✂️ Chunking	Perform semantic chunking for better context retention
🧬 Embedding	Generate vector embeddings using Sentence Transformers
🗃 Vector Storage	Store embeddings and metadata in AstraDB
🔍 Retrieval	Retrieve relevant chunks using HNSW-based vector search
🪄 Reranking	Enhance relevance and diversity with BM25 or MMR
🧠 LLM Prompting	Use contextually rich prompts to query LLMs
📄 DOCX Output	Generate final answers and save them as a DOCX report

📌 Highlights & Capabilities
✅ End-to-end RAG pipeline from data ingestion to response generation

✅ Semantic chunking for improved retrieval relevance

✅ Integration of modern vector store (AstraDB) with efficient indexing

✅ Reranking using BM25 and MMR for diverse, high-quality results

✅ Final output rendered in a structured Word document

💡 This project demonstrates how to combine vector databases, semantic embeddings, and LLMs for intelligent document retrieval and generation workflows.
