# 🎬 Movie Recommendation System

> **Discover your next movie — powered by Machine Learning. 🍿**

A lightweight **content-based movie recommendation system** built with Python. It analyzes movie descriptions using **TF-IDF vectorization** and recommends similar movies using **Cosine Similarity**.

## ✨ Features

* 🎯 Content-based movie recommendations
* 🔤 TF-IDF text vectorization
* 📐 Cosine similarity scoring
* 🔎 Custom movie search
* 📊 Top-N recommendations with similarity scores
* ⚡ Simple and easy-to-extend architecture

## 🧠 How It Works

```text
Movie Description
       ↓
   TF-IDF Vectorization
       ↓
 Cosine Similarity
       ↓
 Similar Movies 🎬
```

The project currently works with **12 movies** and generates a **12 × 12 similarity matrix**.

## 🛠️ Tech Stack

* 🐍 Python
* 🐼 Pandas
* 🤖 Scikit-learn
* 📓 Jupyter Notebook

## 🚀 Usage

Run the notebook and call:

```python
recommend_movies("Interstellar")
```

Example output:

```text
Avatar          → 0.434
The Martian     → 0.367
Arrival         → 0.291
Jurassic Park   → 0.201
The Matrix      → 0.168
```

The recommendation function returns movies ranked by their calculated similarity score.

## 📂 Project Structure

```text
Movie-Recommendation-System/
│
├── Movie_Recommendation_System.ipynb
└── README.md
```

## 🚀 Future Scope

* Larger movie datasets
* User preferences & ratings
* Collaborative filtering
* Movie posters and metadata
* Streamlit web application
* Advanced NLP / embeddings

## 👨‍💻 Author

**Paramjeet kaur**

---

⭐ **Built with Python, Machine Learning & a love for movies.**
