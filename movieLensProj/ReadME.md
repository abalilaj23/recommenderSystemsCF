# Collaborative Filtering Model for Movie Ratings Prediction

## The Project

This project creates a collaborative filtering model to predict missing movie ratings from users using **SoftImpute**.

### The MovieLens Dataset

MovieLens is a non-commercial, web-based movie recommender system, created in **1997** by GroupLens, a research lab at the University of Minnesota. The system was designed to gather movie rating data for research purposes. You can access the dataset [here](https://grouplens.org/datasets/movielens/). Several versions are available, and for this project, we will use the **latest smallest dataset** released.

- **Dataset Details:**
  - **Observations**: 100,836
  - **Variables**: `userId`, `movieId`, `rating`
  
For more information on the dataset, you can visit the official [MovieLens README](https://files.grouplens.org/datasets/movielens/ml-latest-small-README.html).

## Custom Code

- **soft_impute.py**: Contains the implementation of the SoftImpute algorithm for matrix completion.
- **functionsCF.py**: Contains custom functions for collaborative filtering.

These custom packages help to predict missing ratings and improve the recommendation system's accuracy.                                          
