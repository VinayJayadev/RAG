# Dive into RAG

This repository contains code for retrieving relevant documents based on a query. It uses a sentence embedding model to convert queries into embeddings, and then finds the most similar documents using a similarity search. 

## Requirements
To run this code, you will need:
- Python 3.x
- `numpy` library
- A sentence embedding model (like `SentenceTransformers` from Hugging Face)
- An indexing system for similarity search (like `FAISS` from Facebook)

   ```bash
   pip install numpy sentence-transformers faiss-cpu
   ```

   
