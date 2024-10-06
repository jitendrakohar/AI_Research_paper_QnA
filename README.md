# RAG Research Paper Q&A with Groq and Llama3

## Overview

RAG Research Paper Q&A is a Streamlit application designed to provide users with a question-and-answer interface for research papers. The application leverages Groq's powerful language model and Hugging Face embeddings to deliver contextually relevant responses based on user queries. It allows users to interact with documents stored in a PDF directory, enabling efficient information retrieval and document similarity searches.

## Features

- **Question & Answering**: Answer user queries based on the context of loaded research papers.
- **Document Embedding**: Embed and index documents using Hugging Face and FAISS for fast retrieval.
- **Contextual Responses**: Generate answers based on provided context to ensure accuracy.
- **Document Similarity Search**: Display similar documents related to user queries.

## Requirements

To run this project, you will need the following:

- Python 3.7 or later
- Streamlit
- Langchain libraries (including `langchain_groq`, `langchain_huggingface`, etc.)
- FAISS for vector search
- PyPDF2 or any other library for PDF document handling
- `python-dotenv` for environment variable management

You can install the required libraries using pip:

```bash
pip install streamlit langchain_groq langchain_huggingface langchain_community faiss-cpu python-dotenv
