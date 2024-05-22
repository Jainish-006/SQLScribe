# SQLScribe

## Overview
SQLScribe is a web application designed to translate English questions into SQL queries seamlessly. This project leverages the power of LangChain, HuggingFace embeddings, and IBM's Granite language model to achieve efficient and accurate translations. The application supports the upload of a PDF file containing the database schema, enabling the model to understand and generate contextually appropriate SQL queries.

## Features
Upload and parse PDF files containing database schemas.
Seamless translation of English questions into SQL queries.
Interactive chat interface for user interaction.
Uses LangChain's document loaders, index creators, and retrieval QA chains.
Powered by HuggingFace embeddings and IBM's Granite language model.

### Prerequisites
Python 3.8 or higher
Streamlit
LangChain
HuggingFace Transformers
wxai_langchain library
Required credentials for IBM Watson Language Model
