# Movie Recommendation System
This project is based on movie recommendation system, which recommends 5 most relevant movies.

The movies are recommended based on the content of the movie you entered or selected. The main parameters that are considered for the recommendations are the genre, director, and top 3 casts. The details of the movies, such as title, genre, runtime, rating, poster, casts, etc., are fetched from TMDB. A content-based recommender system that recommends movies similar to the movie the user likes and analyses the sentiments of the reviews given by the user.
The reviews of each individual movie given by the users are "web-scraped" from the IMDB website, and the reviews are subjected to sentiment analysis, where the model predicts whether the review is positive or negative.

## Dataset
- We have used TMDB 5000 Movie Dataset in order to build movie recommendation engine.
- You can download Dataset from [Here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv).

## Data Description

this dataset contain 4803 Rows and 20 Columns
