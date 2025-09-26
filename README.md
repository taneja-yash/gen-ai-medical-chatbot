# Medical Chatbot
A retrieval-augmented medical chatbot that provides accurate, context-aware answers to user queries using a combination of document embeddings, vector databases, and a state-of-the-art LLM (Gemini-1.5).

## Project Overview
This project demonstrates a complete pipeline for building an AI-powered chatbot:
- Data Extraction – Extracts medical information from PDFs.
- Text Processing – Splits documents into manageable text chunks for efficient retrieval.
- Embedding & Vectorization – Generates semantic embeddings using Hugging Face models.
- Vector Database Integration – Stores embeddings in Pinecone for fast, similarity-based retrieval.
- Retrieval-Augmented Generation (RAG) – Connects embeddings with Gemini LLM to deliver accurate answers to user queries.

## Features
- Automated project setup via template.py and setup.py.
- Semantic knowledge base stored in Pinecone with 384-dimensional vectors.
- Efficient document retrieval using cosine similarity.
- Context-aware responses using retrieval-augmented generation.
- Modular and scalable design for adding new documents or datasets.

## Technologies Used
- Python – Core programming language.
- Hugging Face Transformers – Embedding generation.
- Pinecone – Vector database for semantic search.
- Gemini-1.5 Flash – Large language model for RAG-based responses.
- setuptools – Project packaging and automation.

## Project Structure
medical-chatbot/
├── template.py          # Automates project file structure  
├── setup.py             # Project setup and packaging  
├── data_processing.py   # PDF extraction and text chunking  
├── embeddings.py        # Embedding generation and Pinecone integration  
├── chatbot.py           # RAG chatbot implementation  
├── requirements.txt     # Python dependencies  
└── README.md            # Project documentation  

## Author
Yash Taneja
- Master of Science in Business Analytics, University of Texas at Dallas
- [LinkedIn](https://linkedin.com/in/yash-taneja-07) | [GitHub](https://github.com/taneja-yash)
