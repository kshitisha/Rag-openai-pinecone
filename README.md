# Retrieval-Augmented Generation (RAG) System for Context-Aware Question Answering

This repo contains a simple but effective **RAG (Retrieval-Augmented Generation)** pipeline using:

- **OpenAI** (for language generation)
- **Pinecone** or **FAISS** (for vector similarity search)
- **LangChain** (to link everything together)

## What it does

Given a query, it searches your knowledge base, retrieves relevant chunks, and then feeds them into OpenAI to generate an intelligent response — just like a chatbot with memory!

## 🛠 Tech Stack

| Tool               | Purpose                          |
|--------------------|----------------------------------|
| OpenAI             | LLM for generating answers       |
| Pinecone           | Vector DB for retrieval          |
| FAISS              | Local fallback vector store      |
| LangChain          | Agent framework for chaining     |
| Sentence Transformers | For text embeddings          |



##  License

[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)

This repository is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/).

## Setup Instructions

If running locally:
```bash
pip install -r requirements.txt



