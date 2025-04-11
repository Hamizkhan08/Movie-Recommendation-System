# 🎬 Movie Recommendation System

A web-based Movie Recommender system built with Flask that suggests movies similar to the one you input, using two different NLP models — **Count Vectorizer** and **TF-IDF Vectorizer**. It also includes insightful visualizations on genres, actors, and movie similarity metrics.

## 🚀 Features

- Recommend similar movies using:
  - Count Vectorizer
  - TF-IDF Vectorizer
- Explore genre and actor trends
- View heatmaps showing movie similarity
- Simple and clean UI built with HTML + CSS
- Flask-powered web application

## 📂 Project Structure

├── app.py # Flask application ├── movie_recommender.py # Data preprocessing, model building & saving ├── templates/ │ ├── index.html # Home page for recommendations │ └── charts.html # Visualizations page ├── static/ │ └── charts/ │ ├── top_genres.png │ ├── top_actors.png │ └── similarity_heatmap.png ├── movies.pkl # Processed movie data ├── similarity_count.pkl # Count Vectorizer similarity matrix ├── similarity_tfidf.pkl # TF-IDF similarity matrix ├── tmdb_5000_movies.csv # Movie metadata (from TMDB) ├── tmdb_5000_credits.csv # Cast and crew data (from TMDB) └── README.md
