# Movie Recommendation System

A Flask-based movie recommendation system using content-based filtering and sentiment analysis.

## Features

- Movie recommendations using cosine similarity
- TMDB API integration
- Movie posters and cast information
- Sentiment analysis of movie reviews
- Flask backend with AJAX frontend

## Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- JavaScript
- AJAX
- TMDB API

## How It Works

1. User searches for a movie.
2. Flask recommendation engine finds similar movies.
3. TMDB API provides movie metadata.
4. Results are displayed dynamically using AJAX.

## Run Locally

```bash
pip install -r requirements.txt
python main.py
```