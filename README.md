# Content-Engine

## Overview
The Content Engine is a Python-based system designed to analyze, compare, and extract insights from multiple PDF documents. Leveraging Retrieval Augmented Generation (RAG) techniques, it uses local embedding models and a Large Language Model (LLM) to ensure data privacy and effective document querying.

## Features
- **PDF Parsing**: Extracts and processes content from uploaded PDF documents.
- **Embedding Generation**: Creates vector embeddings for document content using a local embedding model.
- **Vector Store Integration**: Stores embeddings in a local vector store (e.g., ChromaDB) for efficient querying.
- **Interactive Interface**: Utilizes Streamlit to provide a user-friendly interface for querying and comparing document insights.

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository_url>
2. Install dependencies
   pip install -r requirements.txt
3. Run the application
   streamlit run app.py
4.Upload PDF documents and interact with the chatbot interface for document analysis.
Sample Queries
Risk Factors: "What are the risk factors associated with Google and Tesla?"
Revenue Comparison: "What is the total revenue for Google Search?"
Business Model Differences: "What are the differences in the business of Tesla and Uber?"
Notes
Replace placeholder components like OpenAI() with a local LLM for full local processing.
Ensure all dependencies and models are configured before running the application.
