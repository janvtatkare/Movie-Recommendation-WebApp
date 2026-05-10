# CineMatch - Movie Recommendation WebApp

A content-based movie recommendation system. Select a movie and get 5 personalized recommendations with posters.

## Quick Start

**Prerequisites:** Python 3.7+

**Installation:**

```bash
pip install -r requirements.txt
streamlit run app.py
```

Open `http://localhost:8501` in your browser.

## How It Works

- Uses TMDb dataset (5,000 movies with credits)
- Builds a similarity matrix based on genres, keywords, cast, and crew
- Returns top 5 most similar movies with posters from TMDb API

## Tech Stack

- Streamlit (frontend)
- Python, Pandas, NumPy (backend)
- TMDb API (movie posters)

## Files

- `app.py` - Streamlit web app
- `movie_recommender_system.py` - Data processing & model
- `tmdb_5000_movies.csv` & `tmdb_5000_credits.csv` - Datasets
- `Procfile` - Heroku config

## License

Uses data from [The Movie Database (TMDb)](https://www.themoviedb.org/)
