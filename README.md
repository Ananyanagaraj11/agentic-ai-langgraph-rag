\# LangGraph Stateful Agent with RAG



This project implements a stateful AI agent using LangGraph with tool integration and Retrieval-Augmented Generation (RAG).



\## Overview



The agent supports:

\- Math calculation using a calculator tool

\- Document-based question answering using RAG

\- General knowledge questions using a local LLM



The system is built as a graph-based workflow using LangGraph.



\## Architecture



Nodes:

\- decision\_node

\- tool\_node

\- retrieval\_node

\- answer\_node



Routing Logic:

\- Math → Calculator Tool

\- Document-related → RAG Retrieval

\- General → Direct LLM



\## RAG Pipeline



\- Document chunking

\- Embedding generation

\- FAISS vector store

\- Similarity search

\- Context injection into LLM



\## Tech Stack



\- LangGraph

\- LangChain

\- FAISS

\- Ollama (LLaMA3)

\- Python



\## How to Run



1\. Install Ollama

2\. Pull model:

&nbsp;  ollama pull llama3

3\. Install dependencies:

&nbsp;  pip install -r requirements.txt

4\. Run Part 1 and Part 2 notebooks



\## Features Demonstrated



\- Stateful graph workflows

\- Conditional routing

\- Tool orchestration

\- Multi-branch agent design

\- Retrieval-Augmented Generation

