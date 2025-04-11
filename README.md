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

## 🛠️ How It Works

1. **Data Preprocessing**  
   Run `movie_recommender.py` to process the TMDB dataset and generate:
   - Tagged movie descriptions
   - Count/TF-IDF vectors
   - Cosine similarity matrices
   - Visual charts

2. **Web App (Flask)**  
   Run `app.py` to start the web server:
   ```bash
   python app.py

## Usage

- Input a movie title
- Choose a model (Count or TF-IDF)
- Get top 5 similar movie suggestions
- Click on "View Analytics" to explore genre and actor trends

## 🧠 Technologies Used

- Python
- Flask
- Pandas, NumPy, Scikit-learn, NLTK
- Matplotlib, Seaborn
- HTML5, CSS3

## ![image](https://github.com/user-attachments/assets/2002a6a0-ed7c-4d62-9837-a0fac096f0d3)
