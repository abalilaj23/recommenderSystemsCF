# Collaborative Filtering Model for Joke Ratings Prediction

## The Project

This project creates a collaborative filtering model to predict missing joke ratings from users using **SoftImpute**.

### The Jester Dataset

The Jester dataset was developed by **Ken Goldberg**, **Theresa Roeder**, **Dhruv Gupta**, and **Chris Perkins** at UC Berkeley. It contains jokes rated by users on a scale of **-10 to 10**. This version of the dataset includes **1,048,576 observations** and 3 variables:

- `user_id`
- `joke_id`
- `rating`

For more information on the dataset, visit [Jester Dataset](https://eigentaste.berkeley.edu/dataset/).

## Custom Code

- **soft_impute.py**: Contains the implementation of the SoftImpute algorithm for matrix completion.
- **functionsCF.py**: Contains custom functions for collaborative filtering.

These custom packages are used to predict missing joke ratings and enhance the recommendation system's performance.
