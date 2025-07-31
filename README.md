 🔍 langchain-compliance-rag

A prototype project that showcases how Oracle DBAs can leverage **LangChain**, **RAG (Retrieval-Augmented Generation)**, and **vector databases** for smarter compliance and governance.


Objective
============

This project demonstrates:
--------------------------
1) How to integrate Oracle-based data sources with LangChain
2) Use of FAISS for vector storage and semantic search
3) Building a RAG pipeline to answer compliance queries with context

📁 Structure
Here’s the layout of the project files:
---------------------------------------
langchain-compliance-rag/
├──> notebook/
│ | ├──> oracle_rag_pipeline.ipynb # Main RAG pipeline demo
│ | └──> Dataingestion.ipynb # Optional data ingestion steps
├──> requirements.txt # Required packages
├──> README.md # Project overview


Tech Stack
===========
1. LangChain
2. FAISS (Vector store)
3. OpenAI / HuggingFace LLM APIs
4. Oracle DB (for source data)
5. Python

📓 Notebook Demo
=================

You can explore the main pipeline in the notebook here:  
👉 [`oracle_rag_pipeline.ipynb`](oracle_rag_pipeline.ipynb)
