# 🎬 Movie Recommendation AI Project

This project explores advanced techniques in recommender systems using the MovieLens dataset. It covers everything from neural collaborative filtering and explainability to graph-based learning and attention mechanisms.

---

## 🧠 Project Components

📂 **Assignment 1:**  
**Neural Matrix Factorization (NeuMF)** – Combines Generalized Matrix Factorization (GMF) and Multi-Layer Perceptron (MLP) to model user-item interactions and predict preferences in implicit feedback settings.

📂 **Assignment 2:**  
**Explainable AI in Recommender Systems** – Enhances the model with user demographics and movie metadata, applying interpretability tools like **LIME**, **SHAP**, and **Captum**.

📂 **Assignment 3:**  
**Graph-based Representation Learning** – Builds a movie similarity graph, uses **random walks** to create training samples, and trains a **Skip-Gram** model to learn movie embeddings.

📂 **Assignment 4:**  
**Attention-based Recommender System** – Introduces **attention mechanisms** to dynamically focus on the most relevant features, improving personalization and performance.

📑 **Presentation:**  
A summary PDF that outlines all assignments, methods used, and results.

---

## 📊 Dataset: MovieLens

We used the MovieLens datasets in various sizes:

### 🎞️ MovieLens 100K
- 100,000 ratings from 943 users on 1,682 movies.
- Each user has rated at least 20 movies.
- Format: `<userID, itemID, rating, timestamp>`

Used in:
- Assignment 1: Transformed into **implicit feedback** (positive = 1, others = 0)
- Assignment 2: Merged with metadata for **explainability**

### 🎞️ MovieLens Latest Small
- Around 100,000 ratings with **enhanced metadata** (titles, genres, release dates).
- Used in Assignment 3 for graph-based recommendation.

You can get the datasets from: [https://grouplens.org/datasets/movielens/](https://grouplens.org/datasets/movielens/)

---

## 🛠️ Tech Stack

- Python, PyTorch
- Captum, SHAP, LIME
- Scikit-learn, Pandas
- NetworkX
- Matplotlib, Seaborn

---

## 👥 Authors

- Ozgur Gumus

---

## 📁 Folder Structure

