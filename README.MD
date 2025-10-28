RAG-WORKSHOP
End-to-end RAG (Retrieval-Augmented Generation) workshop demonstrating how to build a local AI assistant using LangChain, ChromaDB, and Ollama. Includes setup instructions, environment configuration, and practical notebook examples for document-based question answering.

This repository contains a complete Retrieval-Augmented Generation (RAG) workshop designed to help you build and run a local LLM-powered assistant using LangChain, ChromaDB, and Ollama.

HOW TO RUN: Follow the instructions from the SETUP.HTML file

RAG_Workshop/
├── data/ # PDF documents for RAG demos
├── rag_env/ # virtual python environment
├── RAG_Demo-venv.ipynb # Main workshop notebook
├── test_rag_setup.py # Environment verification script (optional)
└── SetUp.html # Original workshop setup guide

MY RAG SYSTEM
TOPIC CHOSEN/DATA USED: Environment and Development(NPTEL)/Used lecture PDFs 

WHAT I CHANGED:
Documents: Contains PDFs based on the subject,"Environment and Development"
Chunking: chunk size: 400, overlap: 50
Retrieval: similarity, k = 5

Test Question
What is ecofeminism?
