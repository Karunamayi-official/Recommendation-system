# 🎬 Content-Based Movie Recommender System

This repository contains a simple **content-based movie recommendation system** built with Python, scikit-learn, and an interactive Google Colab app.  
It suggests movies that are similar based on their plot overviews using **TF-IDF vectorization** and a **sigmoid kernel** for similarity.

---

## 📂 Dataset

- **Source:** [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)  
- Files used:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv` (optional for future metadata improvements)

---

## 🚀 Features

✅ Clean movie overviews and handle missing data  
✅ Convert text to numerical vectors using **TF-IDF**  
✅ Compute pairwise similarity with a **sigmoid kernel**  
✅ Map movie titles to DataFrame indices for fast lookup  
✅ Recommend the top N similar movies given a title  
✅ **Colab mini app** with an interactive text box — get recommendations instantly!



