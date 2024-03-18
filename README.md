# *Movie Recommendation System*

This is a simple movie recommendation system built using Python and Streamlit. The system recommends movies based on their similarity to the selected movie. The similarity is calculated using cosine similarity on movie descriptions, genres, keywords, cast, and crew.

### Components

1. *Data Preprocessing*: The system preprocesses the movie data by cleaning, transforming, and extracting relevant features such as genres, keywords, cast, and crew.

2. *Feature Engineering*: It creates a unified set of 'tags' by combining movie descriptions, genres, keywords, cast, and crew. This helps in building a feature matrix for similarity calculation.

3. *Model Building*: Cosine similarity is used to measure the similarity between movies based on their tags. The model recommends movies that are most similar to the selected movie.



### File Structure

- *movie_recommendation.py*: Contains the Python code for preprocessing, model building, and recommendation functions.
- *tmdb_5000_movies.csv*: Dataset containing movie details.
- *tmdb_5000_credits.csv*: Dataset containing movie credits.


### Dependencies

- *Pandas*: For data manipulation and preprocessing.
- *NumPy*: For numerical operations.
- *Scikit-learn*: For cosine similarity calculation.
- *NLTK*: For text processing and stemming.


### References

- The movie dataset used in this project is sourced from [TMDb (The Movie Database)](https://www.themoviedb.org/).
- Stemming technique is applied using NLTK's PorterStemmer.
- Cosine similarity calculation is done using Scikit-learn.


### Future Improvements

- Implementing more advanced recommendation algorithms like collaborative filtering.
- Enhancing user interface with additional features like search, filters, and ratings.
- Optimizing model performance for larger datasets.
