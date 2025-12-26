# Semantic Book Recommender

---

## `Project_Overview`
This project implements a semantic and emotion-aware book recommendation system using NLP and vector embeddings.  
The system recommends books based on natural language descriptions, categories, and emotional tone instead of keyword matching.

---

## `Problem_Statement`
Traditional book recommendation systems rely on ratings or keyword search and fail to capture user intent and emotions.  
The objective is to build a robust semantic recommendation pipeline that understands meaning, context, and mood.

---

## `Dataset`
Source: Public book metadata dataset  

Data includes:
- Book title and author  
- Book description  
- Simplified category  
- Emotion scores (joy, sadness, anger, fear, surprise)  

---

## `Approach`
The project follows a structured NLP and semantic search pipeline:

- Data cleaning and exploration  
- Category simplification  
- Emotion extraction from descriptions  
- Sentence embedding generation  
- Vector similarity search  
- Emotion-based ranking  

---

## `Text_Preprocessing`
- Cleaned and normalized book descriptions  
- Removed missing and noisy entries  
- Standardized author and category information  
- Prepared text for embedding generation  

---

## `Feature_Extraction`
- Sentence embeddings using transformer-based models  
- Embeddings capture semantic meaning for similarity comparison  

---

## `Models_Used`
- Sentence-Transformers (`all-MiniLM-L6-v2`)  
- Pretrained NLP models for emotion analysis  

---

## `Vector_Search`
- ChromaDB used as vector store  
- Cosine similarity used for semantic retrieval  
- Top-k relevant books selected before filtering  

---

## `Results`
- Semantically relevant book recommendations achieved  
- Emotion-based ranking improves personalization  
- System performs well for intent- and mood-based queries  

---

## `Tech_Stack`
- Python  
- NumPy, Pandas  
- Hugging Face Transformers  
- Sentence Transformers  
- LangChain  
- ChromaDB  
- Gradio  
- Jupyter Notebook  

---
