# agentic-ai-langgraph-rag

Stateful AI agent built with LangGraph featuring tool orchestration and Retrieval-Augmented Generation (RAG) using FAISS and Ollama.

## Overview

This project implements a graph-based stateful AI agent that supports:
- Math calculation using a calculator tool
- Document-based question answering using RAG
- General knowledge questions using a local LLM

## Architecture

Nodes:
- decision_node
- tool_node
- retrieval_node
- answer_node

Routing Logic:
- Math → Calculator Tool
- Document-related → RAG Retrieval
- General → Direct LLM

## RAG Pipeline

- Document chunking
- Embedding generation
- FAISS vector store
- Similarity search
- Context injection into LLM

## Tech Stack

- LangGraph
- LangChain
- FAISS
- Ollama (LLaMA3)
- Python

## How to Run

1. Install Ollama  
2. Pull model:  
   `ollama pull llama3`  
3. Install dependencies:  
   `pip install -r requirements.txt`  
4. Run Part 1 and Part 2 notebooks

## Features Demonstrated

- Stateful graph workflows
- Conditional routing
- Tool orchestration
- Multi-branch agent design
- Retrieval-Augmented Generation