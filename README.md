# RAG with Chroma and FAISS

This repository contains two notebooks demonstrating Retrieval-Augmented Generation (RAG) implementations using Chroma and FAISS as vector stores.

## Files
- `RAG_with_Chroma_VectorDBa.ipynb`: Implementation of RAG using Chroma as the vector store.
- `RAG_with_Faiss_VectorDB.ipynb`: Implementation of RAG using FAISS as the vector store.

## Requirements
Install the required Python packages using:
```bash
pip install -r requirements.txt

## How to Use

    Replace the dataset path in the code:

    folders = glob.glob(r"path_to_your_dataset/*")

    Update path_to_your_dataset with the location of your knowledge base.

    Run the notebooks to experiment with RAG.

## Dataset

The fake dataset used in this repository is not included. You should provide your dataset in a folder where each subfolder contains multiple files for processing.
Notes

    Chroma uses SQLite as the backend.
    FAISS requires the faiss-cpu or faiss-gpu library.
