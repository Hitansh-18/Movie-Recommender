# 🎬 Movie Recommender System

A content-based Movie Recommender System that recommends similar movies based on their content and features.

## 🚀 Live Demo

[Click here to try the application](https://movie-recommender-eh862qs2bak5rknrnpg85h.streamlit.app/)

## 📌 Features

- Select a movie from the available collection
- Get 5 similar movie recommendations
- Display movie posters using the TMDB API
- Interactive and user-friendly interface built with Streamlit

## 🧠 Machine Learning Approach

The recommendation system uses a **content-based filtering approach**.

Movie information such as genres, keywords, cast, crew, and overview is combined into textual tags. These tags are processed using **Natural Language Processing (NLP)** techniques.

The project uses:

- Bag of Words
- Text Vectorization
- Cosine Similarity
- Porter Stemming

The similarity between movies is calculated using cosine similarity, and the five most similar movies are recommended.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK
- Streamlit
- TMDB API

## 📂 Project Structure

```text
Movie-Recommender-System/
│
├── app.py
├── movies_dict.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
└── Movie_Recommender_System.ipynb
