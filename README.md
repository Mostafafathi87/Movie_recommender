# Movie_recommender
A movie recommendation system using collaborative filtering and Naive Bayes classification on the MovieLens 1M dataset. This project processes user ratings, tunes hyperparameters, and evaluates model performance across various metrics like accuracy, precision, and AUC. Built with Python, scikit-learn, pandas, and numpy
# Movie Recommender System

This project implements a basic recommender system using collaborative filtering techniques to predict whether a user would like a specific movie. The system is built with `scikit-learn`, `pandas`, and `numpy` to preprocess data and train a Naive Bayes classifier on user ratings.

## Features

- **Data Preparation**: Preprocesses ratings, movies, and users data files.
- **Collaborative Filtering**: Uses user-movie interaction to predict movie ratings.
- **Hyperparameter Tuning**: Tunes Naive Bayes parameters with cross-validation.
- **Evaluation**: Evaluates model accuracy, precision, recall, F1-score, AUC, and other classification metrics.

## Project Structure

- `MovieRecommender`: The main class, containing methods for data loading, preparation, hyperparameter tuning, and model training/evaluation.

## Data

The model uses the **MovieLens 1M** dataset, which includes:
- `ratings.dat`: Contains user ratings for movies.
- `movies.dat`: Contains movie metadata.
- `users.dat`: Contains user demographic data.

Each of these files should be stored in the `ml-1m` directory.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mostafafathi87/movie-recommender.git
   cd movie-recommender
