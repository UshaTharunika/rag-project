# Day 3 – RAG Implementation

## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline using:
- LangChain
- ChromaDB (Vector Database)
- HuggingFace (GPT-2 model)

## Steps Implemented
1. Loaded PDF documents
2. Split into chunks using RecursiveCharacterTextSplitter
3. Stored embeddings in ChromaDB
4. Built a semantic retriever
5. Created a RAG pipeline
6. Tested with multiple questions

## Note
Due to limitations of lightweight models like GPT-2 in Google Colab, the generated answers may:
- Contain repetition
- Not fully align with the retrieved context

However, the retrieval pipeline is working correctly.

## Conclusion
This project demonstrates how semantic search and RAG systems work using vector databases and LLMs.
