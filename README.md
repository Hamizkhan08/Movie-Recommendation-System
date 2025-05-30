# 🎬 Movie Recommendation System

A web-based Movie Recommender system built with Flask that suggests movies similar to the one you input, using two different NLP models — **Count Vectorizer** and **TF-IDF Vectorizer**. It also includes insightful visualizations on genres, actors, and movie similarity metrics.

![WhatsApp Image 2025-04-11 at 8 32 58 PM](https://github.com/user-attachments/assets/52d7c8ca-32bf-42c3-98c2-1499c07c66a2)




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

## 📁 Dataset Source
TMDB 5000 Movie Dataset on Kaggle

## Made By Hamiz Khan
