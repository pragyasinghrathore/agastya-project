# Agastya Project — Retrieval-Augmented Generation (RAG) Pipeline

## Overview

Agastya is an end-to-end **Retrieval-Augmented Generation (RAG)** pipeline designed to demonstrate practical implementation of:

- Data preprocessing and semantic chunking  
- Vector embedding generation  
- Persistent vector storage using ChromaDB  
- Context-aware retrieval using LangChain  
- Clustering analysis of embeddings  

The project is structured to be **modular, reproducible, and scalable**, with clear separation between data processing, retrieval logic, and analytical components.

---

## Project Structure

Agastya_Project/
│
├── Agastya_pipeline.ipynb
├── Rag_LangchainopenAI.ipynb
├── Rag_Langchaingemini.ipynb
├── Cluster_analysis.ipynb
│
├── .gitignore
└── README.md

---

## Notebooks

### 1. Agastya_pipeline.ipynb
- Loads and preprocesses raw textual data  
- Performs semantic chunking  
- Generates vector embeddings  
- Stores embeddings persistently using ChromaDB  
- Automatically creates the required folder structure  

This notebook builds the **core embedding pipeline** of the project.

---

### 2. Rag_LangchainopenAI.ipynb
- Connects to the vector database  
- Implements Retrieval-Augmented Generation (RAG)  
- Performs semantic similarity search  
- Generates contextual responses using retrieved documents  

Demonstrates practical RAG system implementation using OpenAI-based models.

---

### 3. Rag_Langchaingemini.ipynb
- Implements RAG using Gemini-based language models  
- Allows comparison between different LLM backends  
- Demonstrates flexibility in model integration  

---

### 4. Cluster_analysis.ipynb
- Applies clustering techniques to embedding vectors  
- Analyzes semantic groupings within the dataset  
- Explores structural relationships and topical similarity  

---

## How to Run

1. Run `Agastya_pipeline.ipynb`  
   → Generates processed data and vector embeddings  

2. Run `Rag_LangchainopenAI.ipynb` or `Rag_Langchaingemini.ipynb`  
   → Enables retrieval-based querying  

3. Run `Cluster_analysis.ipynb`  
   → Performs embedding-level analysis  

---

## Technologies Used

- Python  
- LangChain  
- ChromaDB  
- Vector Embeddings  
- Retrieval-Augmented Generation (RAG)  
- Unsupervised Clustering  

---

## Data & Embeddings

Large generated files such as:

- Processed datasets  
- Embedding JSON files  
- ChromaDB persistence files  

are intentionally excluded from version control using `.gitignore`.

All artifacts are generated locally by running the main pipeline notebook.

---

## Future Work

The long-term vision of Agastya is to expand into a broader semantic knowledge system focused on **ancient scriptures and traditional knowledge sources**.

Planned improvements include:

- Incorporating additional datasets related to ancient scriptures  
- Expanding corpus coverage for deeper contextual retrieval  
- Improving semantic chunking strategies  
- Optimizing embedding storage and indexing  
- Evaluating different embedding models for domain-specific performance  

The goal is to evolve Agastya into a **scalable retrieval system** capable of structured exploration of historical and philosophical texts.

---

## Purpose

This project demonstrates hands-on experience with:

- Designing end-to-end RAG pipelines  
- Working with vector databases  
- Building modular NLP systems  
- Performing embedding-based analysis  

It is intended to showcase practical skills relevant to **AI/ML engineering and applied NLP roles**.
