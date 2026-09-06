# Nestle-HR-Policy-RAG-Model

RAG Model on Nestlé’s 2012 HR Policy

## 📖 Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline to enable natural language querying of Nestlé’s 2012 HR policy document. The system ingests the PDF, generates embeddings, retrieves relevant chunks, and produces contextual answers using a large language model. The goal is to make complex HR policies easily searchable and understandable.

## ⚙️ Tech Stack
- Data Ingestion: PyPDFLoader, RecursiveCharacterTextSplitter  
- Embeddings & Storage: Google GenerativeAI Embeddings, FAISS vector database  
- Retrieval & Prompting: LangChain Retriever, ChatPromptTemplate  
- LLM: Gemini‑3.5‑Flash  
- Output Parsing: StrOutputParser  
- Evaluation: ROUGE metrics (rouge1)  
- Frontend: Gradio UI  

## 🚀 Features
- Query HR policy in plain English.  
- Retrieves top‑k relevant chunks for accurate context.  
- Generates precise, contextual answers using Gemini LLM.  
- Evaluates response quality with ROUGE metrics.  
- Interactive Gradio interface for user queries.  

----------------IMPORTANT--------------------
Make sure to insert YOUR GEMINI API KEY IN embeddings column and while creation of llm model.
