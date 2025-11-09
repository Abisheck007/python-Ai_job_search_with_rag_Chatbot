🤖 Python AI Job Search with RAG Chatbot
Project Overview
This project implements an AI-powered chatbot designed to assist with job search by leveraging the Retrieval-Augmented Generation (RAG) framework. The RAG architecture allows the language model to retrieve relevant information from a specific knowledge base (e.g., job descriptions, resume data) before generating a response, leading to more accurate, contextual, and up-to-date answers than a standalone LLM.

This chatbot is specifically tailored to handle queries related to job requirements, career path guidance, and document analysis (like comparing a resume to a job description).

✨ Features
Contextual Q&A: Answers job-related questions based on provided documents, ensuring high relevance and avoiding common LLM hallucinations.

Vector Database Integration: Uses a modern vector database (e.g., ChromaDB, FAISS) for efficient semantic search and retrieval.

Modular Design: Separates the data processing, model loading, and chatbot interface for easy maintenance and expansion.

Local Execution: Built to run locally using Python, making it accessible for personal use and development.

🛠️ Tech Stack
Language: Python

Core Libraries: LangChain, Hugging Face Transformers (for embeddings/LLM), ChromaDB or FAISS (for vector storage).

Web Interface (Optional): Streamlit or Gradio (if a UI is implemented).

⚠️ Important Note on Model Files
Due to their substantial size and GitHub's file size limitations, the pre-trained LLM and final fine-tuned model files (e.g., checkpoints, weights) for the RAG model have not been saved or uploaded to this repository.

To run the project, you will need to:

Download a small, suitable LLM from Hugging Face or use an external API (like OpenAI or Gemini) by configuring your API key in the .env file.

The provided code is configured to dynamically load a suitable model during the setup process, or to use the configured API. Please refer to the specific setup script within the Rag_model_and_chatbot/ directory for details on the required model.
