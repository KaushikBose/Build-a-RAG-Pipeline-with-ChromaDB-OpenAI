# Build-a-RAG-Pipeline-with-ChromaDB-OpenAI
This project demonstrates a practical Retrieval-Augmented Generation (RAG) workflow in Python using LangChain. It loads content from a Wikipedia page, splits it into chunks, generates embeddings with an OpenAI-compatible model via OpenRouter, stores them in a local Chroma vector database, and answers questions using the retrieved context.

# RAG Pipeline with ChromaDB and OpenRouter

# Description:
This project showcases a simple yet practical Retrieval-Augmented Generation (RAG) workflow built with Python and LangChain. It loads content from a public Wikipedia page, splits it into smaller text chunks, generates embeddings using an OpenAI-compatible model through OpenRouter, stores them in a local Chroma vector database, and uses a language model to answer questions based on the retrieved context.

The example demonstrates the core building blocks of a RAG system:

document loading from a web source
text chunking
embedding generation
vector storage and retrieval
question answering using context-aware prompting

# Technologies Used:
Python
LangChain
Chroma
OpenRouter
Wikipedia
