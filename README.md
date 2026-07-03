# RAG Chatbot using LangChain and Ollama

## Overview

This project is a beginner-friendly implementation of a Retrieval-Augmented Generation (RAG) pipeline developed in a Jupyter Notebook. It demonstrates how external information can be retrieved from a knowledge source and provided to a Large Language Model (LLM) to generate more accurate responses. The current version focuses on building the core RAG pipeline. In the future, this project can be extended by adding a user interface (such as Streamlit or Flask), supporting multiple document formats, and deploying it as a complete application.

## Features

* Load and process data (such as YouTube transcripts or documents)
* Split text into smaller chunks
* Generate text embeddings
* Store embeddings in a FAISS vector database
* Retrieve relevant context based on a user's query
* Generate answers using an Ollama language model through LangChain

## Technologies Used

* Python
* Jupyter Notebook
* LangChain
* FAISS
* Ollama
* Sentence Transformers
* YouTube Transcript API

## Project Workflow

1. Load the data source.
2. Split the text into smaller chunks.
3. Generate embeddings for each chunk.
4. Store embeddings in a FAISS vector store.
5. Retrieve the most relevant chunks based on the user's query.
6. Pass the retrieved context to the language model.
7. Generate and display the response within the Jupyter Notebook.
