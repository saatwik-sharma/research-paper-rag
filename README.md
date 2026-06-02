# Research Paper Question Answering System using RAG

## Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline for querying and comparing research papers. Users can ask questions about uploaded PDF papers, and the system retrieves relevant document chunks before generating answers using a local Large Language Model.

## Features

* PDF document ingestion
* Automatic text chunking
* Semantic search using embeddings
* FAISS vector database
* Research paper question answering
* Multi-document comparison
* Fully local execution using Ollama

## Tech Stack

* Python
* LangChain
* FAISS
* Sentence Transformers
* Ollama
* Llama 3.2

## Workflow

1. Load research papers from PDF files.
2. Split documents into smaller chunks.
3. Generate embeddings using Sentence Transformers.
4. Store embeddings in FAISS.
5. Retrieve relevant chunks based on user queries.
6. Generate answers using a local LLM.

## Example Queries

* What problem does BERT solve?
* How does GPT-3 perform pre-training?
* Compare BERT and GPT-3 methodologies.
* What are the limitations discussed in the paper?

## Future Improvements

* Hybrid search
* Reranking
* Source citations
* Better comparison prompts
* Larger local language models

## Author

Saatwik Sharma
