# Document Embeddings using Doc2Vec

This project demonstrates how to generate document-level embeddings using the Doc2Vec model. Unlike average Word2Vec embeddings, Doc2Vec learns vector representations directly for entire documents.


## 📌 Overview

Doc2Vec (Paragraph Vector) is an extension of Word2Vec that creates fixed-length vector representations for sentences or documents. These embeddings capture semantic meaning and can be used for similarity comparison and document analysis.


## ⚙️ What This Project Does

- Preprocesses sample text documents  
- Tags documents for Doc2Vec training  
- Trains a Doc2Vec model  
- Generates vector embeddings for each document  
- Infers embedding for a new query sentence  
- Finds most similar documents using cosine similarity  


## 🛠 Libraries Used

- Python  
- gensim  
- NLTK  
- NumPy  

## ✅ Outcome

The model produces learned document embeddings and ranks documents based on semantic similarity with a given query.
