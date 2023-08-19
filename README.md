# Content-based-movie-recommendation
A movie recommendation system suggests movies to users based on their preferences and other relevant factors. The goal of this is to help users discover new movies that they might enjoy watching. This project is based on Content-based recommendation. 
# Libraries:
Numpy, Pandas, Sklearn, nltk
# Datasets:
tmdb_5000_movies, tmdb_5000_credits
# Workflow:
1. Preprocessiong:
- Remove missing data
- Remove duplicate data
- Take only the name of genres, keywords from the dictionary of genres, keywords
- Take top 5 casts' names from the dictionary of cast
- Take director names from crew
- Make overviews a list for the ease of concatenation later
- Remove the spaces between names of genres, casts, crew to avoid duplication
2. Vectorization of all the movies
3. Measure cosine distances and based on that find the most similar movies
