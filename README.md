# 💼 LinkedIn Job Recommender System

This project builds a personalized job recommendation system inspired by platforms like LinkedIn. It explores various deep learning techniques such as **Neural Collaborative Filtering (NCF)** and **NeuMF**, using skill and profile embeddings to learn user–job affinities in data-sparse scenarios.

The system addresses the cold-start problem by generating pseudo-interactions using skill similarity and user profile embeddings derived from Word2Vec and TF-IDF. These synthetic interactions helped bootstrap training when real application data was unavailable.

---

## 📚 Project Overview

- ✅ Skill-based similarity using Word2Vec/TF-IDF + Cosine Similarity
- ✅ Neural Collaborative Filtering (NCF)
- ✅ NeuMF (Neural Matrix Factorization)
- ✅ Evaluation using Top-K Accuracy, NDCG@K, and confusion matrix
- ✅ Synthetic interaction generation to simulate user–job feedback

---

## 🧠 Core Models

- `Deep_Learning_Models/NCF&NeuCF.ipynb`: Implementation of NCF and NeuMF
- Embedding pipelines and preprocessed features are used to simulate sparse real-world feedback.

---

## 📦 Raw Dataset

Due to GitHub’s 100MB file limit, the raw dataset is hosted externally on Google Drive.

🔗 [Download All Datasets (Google Drive Folder)](https://drive.google.com/drive/folders/1eAIcaP0HpFN5w9unIEurW8YsAIoZDCID?usp=sharing)

