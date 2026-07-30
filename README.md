# 🎬 What2Watch - Movie Recommendation System

Discover your next favorite movie with **What2Watch**, a Content-Based Movie Recommendation System built using **Python**, **Machine Learning**, **NLP**, and **Streamlit**. The application analyzes movie metadata and recommends similar movies in seconds.

🌐 **Live Demo:** https://what2watch-recommender.streamlit.app/

---

## ✨ Features

- 🎥 Content-Based Movie Recommendations
- 🔍 Search from 5000+ Movies
- 🖼️ Movie Posters via TMDB API
- ⚡ Fast Recommendation Engine
- 💻 Interactive Streamlit Web App
- 📱 Simple & Responsive Interface

---

## 🛠️ Tech Stack

**Languages**
- Python

**Libraries**
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Requests

**Machine Learning**
- Natural Language Processing (NLP)
- CountVectorizer
- Cosine Similarity

**Frontend**
- Streamlit

**API**
- TMDB API

---

## ⚙️ How It Works

1. Merge TMDB Movies and Credits datasets.
2. Preprocess movie metadata.
3. Create feature tags using genres, cast, crew, keywords, and overview.
4. Convert text into vectors using CountVectorizer.
5. Calculate similarity using Cosine Similarity.
6. Recommend the Top 5 most similar movies.

---

## 📂 Project Structure

```
Movie-Recommender-System/
├── app.py
├── movie_recommender.ipynb
├── movies.pkl
├── requirements.txt
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/gourav009254/Movie-Recommender-System.git
```

Move into the project directory

```bash
cd Movie-Recommender-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📊 Dataset

- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

---

## 🚀 Future Improvements

- Movie ratings
- Genre-based filtering
- Release year filtering
- Watchlist feature
- Trailer integration
- Hybrid recommendation model

---

## 👨‍💻 Author

**Gourav**

- GitHub: https://github.com/gourav009254

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.