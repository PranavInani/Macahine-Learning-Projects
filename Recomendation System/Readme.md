# Content-Based Recommendation System

This repository contains a content-based recommendation system built using the MovieLens dataset. The system recommends movies based on their content, such as titles and genres.
## Overview

The content-based recommendation system is implemented using the following steps:

  1. Data Loading: The MovieLens dataset is downloaded and loaded into a Pandas DataFrame.
  2. Data Preprocessing: The dataset is preprocessed to extract relevant features for recommendation.
  3. Feature Extraction:
       - TF-IDF Vectorization: The TfidfVectorizer is used to vectorize the movie titles.
       - One-Hot Encoding: The genres are one-hot encoded to represent the categorical data.
  4. Similarity Calculation: Cosine similarity is computed between the movies to find similar ones based on the extracted features.
  5. Recommendation: Given a movie, the system recommends similar movies based on content.

## Dependencies

The project uses the following Python libraries:

    pandas
    numpy
    matplotlib
    scikit-learn
    nltk
    scipy

## Dataset

The MovieLens dataset is used in this project. It contains metadata of movies, including titles and genres, which are essential for building the recommendation system.

## Acknowledgements

- The MovieLens dataset is provided by GroupLens.
- Inspiration for content-based recommendation systems is drawn from various online resources and academic materials.
