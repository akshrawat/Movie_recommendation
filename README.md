# Movie_recommendation

# About dataset

## Context

IMDB (Internet Movie Database) is one of the largest online databases for movies and television shows, providing comprehensive information about movies, including ratings and reviews from its vast user base. The IMDB ratings are widely used as a benchmark for the popularity and success of movies.

This dataset contains the top 250 rated movies on IMDB as of 2021, providing a snapshot of the most popular and highly rated movies of recent times. By analyzing this dataset, one can gain insights into the movie industry, such as trends in movie ratings and popular genres.

The data was scraped from the IMDB website for educational purposes and to provide a publicly available dataset for others to use and build upon.

## Source

The data for this dataset was scraped from the IMDB website (www.imdb.com). The top 250 movies were selected based on their IMDB ratings, and information such as movie title, director, cast, rating, votes, and year of release was collected. No data was altered or modified in any way, and all data was collected in accordance with IMDB's terms of use


# Libraries

   - numpy
   - pandas
   - matplotlib
   - nltk
   - sci-learn

# Algorithms

    There are two recommendation techniques: 
    1) Content based filtering - using description/plot for recommeding similar stuff 
    2) Collaborative filtering - using users past behavior for recommending
    
    Here I have used Content based filtering which uses cosine similarity between movies for best results.
