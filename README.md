# Movie Recommender System

This project implements a **Movie Recommender System** using **collaborative filtering** with Python and Pandas. The system suggests movies similar to those that a user has already rated.

## Features

- Uses user-based collaborative filtering
- Computes movie-to-movie similarity
- Generates personalized movie recommendations
- Uses correlation to identify similar movies

## How It Works

1. Load movie ratings dataset
2. Create a user-item matrix using pivot table
3. Calculate correlation between movies
4. Multiply correlations by user's ratings to weight preferences
5. Aggregate and sort movies to produce top recommendations

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
