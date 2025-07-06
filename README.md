# LLM RAG Pipeline

A Retrieval-Augmented Generation (RAG) pipeline built with Flask, LangChain, FAISS, and OpenAI to answer natural language questions based on uploaded PDF documents.

---

## Features

- Upload unstructured PDFs
- Extract, clean, and chunk text
- Embed text into a vector store (FAISS)
- Query via OpenAI-powered LLM using relevant chunks
- Modular design with extensible architecture
- REST API powered by Flask

---

## Tech Stack

| Layer            | Tools                            |
|------------------|----------------------------------|
| Ingestion        | PyMuPDF                          |
| Cleaning/Chunking| Regex, LangChain                 |
| Embedding        | OpenAI Embeddings + FAISS        |
| LLM              | OpenAI via LangChain             |
| API              | Flask                            |
| Environment      | python-dotenv                    |
| Optional         | Airflow, Streamlit (coming soon) |

---

## Getting Started

### Clone the Repo

```bash
git clone https://github.com/shivaahir158/llm_rag_pipeline.git
cd llm_rag_pipeline
