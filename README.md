# 🩺 PlantDoctor RAG: AI-Powered Plant Health Assistant

A specialized RAG (Retrieval-Augmented Generation) system designed to diagnose plant diseases and provide expert care advice. It uses a sophisticated architecture involving **FastAPI**, **Qdrant**, and multiple LLM providers.

## 🚀 Key Features
- **Hybrid Search:** Combines semantic search with specialized chunking for accurate retrieval.
- **Multi-LLM Support:** Integrated with **OpenAI** and **Cohere** for high-quality generation.
- **Vector Database:** Uses **Qdrant** for efficient high-dimensional vector storage.
- **Persistence:** Integrated with **Firebase** for user authentication and data management.
- **Advanced NLP:** Includes automated summarization and intelligent document chunking.

## 🏗 Architecture
- **Core:** Domain-driven design with clear separation of adapters and infrastructure.
- **Vector Store:** Qdrant (managed via `qdrant-client`).
- **Embeddings:** `sentence-transformers`.
- **Summarization:** Hugging Face pipelines.
