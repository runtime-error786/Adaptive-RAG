## Overview

This project integrates a retrieval-augmented generation (RAG) system using LangChain and a local LLM (Llama) model. The goal is to retrieve relevant documents based on a user's query, generate answers from these documents, and perform various evaluation steps such as checking document relevance, hallucination grading, and more.

## Key Features

Document Retrieval: Retrieves relevant documents from a Chroma vectorstore or web search based on a user's query.


Document Relevance Grading: Filters retrieved documents to ensure they are relevant to the user's question.


Query Rewriting: Improves the user's question for better document retrieval performance.


Answer Generation: Uses RAG to generate answers based on the retrieved documents.


Web Search: Routes questions outside the vectorstore's scope to a web search tool.

![output](https://github.com/user-attachments/assets/df8903b2-f57d-4a11-9104-4c6ee3c512aa)
