**AI-Powered Document Question Answering System**

A Retrieval-Augmented Generation (RAG) system that enables users to upload documents and ask natural language questions about their content.

**Overview**

This project combines semantic search and Large Language Models to generate context-aware answers from uploaded documents.

Instead of relying solely on the LLM's pre-trained knowledge, the system retrieves relevant document sections using vector similarity search and uses them as context for answer generation.

** Features**

- Document Upload
- Text Extraction
- Document Chunking
- Embedding Generation
- Semantic Search
- Retrieval-Augmented Generation (RAG)
- Context-Aware Question Answering

**Tech Stack**

** Backend**
- Python
- Flask

**NLP & AI**
- Sentence Transformers
- Hugging Face FLAN-T5
- Scikit-learn

**Vector Search**
- FAISS

**Architecture**

User Query
↓
Sentence Transformer
↓
Query Embedding
↓
FAISS Similarity Search
↓
Relevant Document Chunks
↓
FLAN-T5
↓
Generated Answer

**Future Improvements**

- Multi-document support
- Chat history memory
- PDF OCR support
- Hybrid Search
- Deployment using Docker and AWS

## Status

Repository is currently being organized and documented.
Source code and deployment instructions are being added.
