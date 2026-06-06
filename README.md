# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using Python, Pandas, Scikit-learn, and Streamlit.

## Features

* Recommend top 10 similar movies based on content similarity
* Display movie posters using TMDB API
* Show movie overview before generating recommendations
* Display similarity percentage for recommended movies
* Interactive web application built with Streamlit

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* TMDB API

## Machine Learning Concepts Used

* Feature Engineering
* CountVectorizer
* Cosine Similarity
* Content-Based Recommendation System

## Dataset

TMDB Movie Metadata Dataset from Kaggle.

Files used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

## How to Run

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Generate movie_data.pkl by running the notebook

```bash
Movie_Recommendation_System.ipynb
```

3. Start the Streamlit application

```bash
python -m streamlit run app.py
```

## Project Structure

* app.py – Streamlit application
* Movie_Recommendation_System.ipynb – Data preprocessing and model creation
* movie_data.pkl – Processed movie data and similarity matrix
* requirements.txt – Project dependencies

## Screenshot

## Screenshot

![Movie Recommendation System]()

## Author

Yogini Satya Divya Kasarapu
