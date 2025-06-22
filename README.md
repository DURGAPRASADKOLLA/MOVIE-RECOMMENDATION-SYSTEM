For the dataset tmdb_5000_credits use the below link
link:https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv
For the dataset tmdb_5000_movies use the below link
link:https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv


Movie Recommendation System
This project is a simple and efficient Movie Recommendation System built using Python and machine learning techniques. It helps users find movies similar to their favorites based on various features like genre, cast, keywords, and more.

💡 Features
Content-based recommendation using movie metadata

Similarity based on genres, overview, cast, keywords, etc.

Easy-to-use interface (CLI or web-based)

Scalable for large datasets like TMDB or MovieLens

Clean, modular codebase for easy customization

🛠️ Tech Stack
Python

Pandas, NumPy

Scikit-learn (for similarity computation)

Flask / Streamlit (for web app, optional)

Jupyter Notebook (for data analysis & model prototyping)

📂 Dataset
The dataset used is from The Movie Database (TMDB) or MovieLens.

Main fields include:

Title

Genres

Overview

Keywords

Cast & Crew

🚀 How It Works
Data Preprocessing: Clean and merge movie metadata.

Feature Extraction: Combine genres, keywords, cast, etc., into a single text feature.

Vectorization: Use TF-IDF or CountVectorizer to convert text to vectors.

Similarity Calculation: Cosine similarity is used to find similar movies.

Recommendation: Based on the input movie, return the top N most similar movies.
