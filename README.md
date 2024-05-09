Title: Document-Based Question-Answering with LangChain & Pinecone

Project Description

This project demonstrates an effective document-based question-answering system powered by LangChain and Pinecone.
It intelligently extracts answers from a focused set of relevant documents, improving context-awareness and accuracy compared to generic Q&A models.

Key Features

LangChain Integration: Leverages LangChain's framework for streamlining interactions with language models while providing customization and modularity.
Pinecone Vector Store: Employs Pinecone for efficient vectorized document storage, enabling fast semantic search and retrieval of relevant information.
Context-Specific Answers: Delivers answers grounded in provided documents, reducing reliance on potentially unaligned external knowledge.

Installation Instructions

1. Prerequisites

Python 3.x
OpenAI API Key (https://beta.openai.com/account/api-keys)
Pinecone API Key and Environment Information

2. Setup

1-Clone the repository:
Bash
git clone https://github.com/piyushptiwari/Document_based_q-a.git

2-Set environment variables:
Bash
export OPENAI_API_KEY=your_openai_api_key
export PINECONE_API_KEY=your_pinecone_api_key
export PINECONE_ENVIRONMENT=your_pinecone_environment

Running the System

Prepare your documents: Place the documents you want to use as the knowledge base in the ./data directory.
Execute the code: Run provided Jupyter notebook or Python script, which includes functions for document loading, embedding, indexing, and question answering.
