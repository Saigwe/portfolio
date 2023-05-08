# Movie Recommendation System using Python

This is a movie recommendation system that uses the TfidfVectorizer, cosine_similarity, and ipywidgets libraries. The system will clean and process data to recommend movies based on the user's input.

**Libraries Used**

* TfidfVectorizer: This library will help us convert the movie data into a matrix of TF-IDF features. This will be used to find similarities between movies based on their plot summaries.
* cosine_similarity: This library will help us calculate the cosine similarity between movies based on their TF-IDF features.
* ipywidgets: This library will help us create a user interface for the recommendation system.

# Data Cleaning

The dataset used for this recommendation system is the MovieLens dataset. We will only use the movies.csv file, which contains information about movies including their titles and plot summaries. Before processing the data, we will remove irrelevant columns and clean the plot summaries by removing any HTML tags, punctuation, and stop words.


# Recommendation System

Once the data has been cleaned and processed, we will use the TfidfVectorizer library to convert the plot summaries into a matrix of TF-IDF features. We will then use cosine_similarity to calculate the cosine similarity between each pair of movies based on their TF-IDF features.

Using ipywidgets, we will create a user interface that allows the user to input a movie title. The system will then recommend 10 movies that are most similar to the user's input based on cosine similarity.

# Next Steps

Here are some next steps to improve the movie recommendation system:

1. Incorporate user ratings into the recommendation system to provide more personalized recommendations.
2. Use a larger dataset to improve the accuracy of the recommendations.
3. Implement a content-based filtering approach to recommend movies based on more than just plot summaries, such as genre, actors, and directors.
4. Use a collaborative filtering approach to recommend movies based on user behavior and preferences.
