# MOVIE-RATING-PREDICTION-WITH-PYTHON
My 2nd project is on MOVIE RATING PREDICTION WITH PYTHON
      MOVIE RATING PREDICTION WITH PYTHON
1. Build a model that predicts the rating of a movie based on
   features like genre, director, and actors. You can use regression
   techniques to tackle this problem.
   The goal is to analyze historical movie data and develop a model
   that accurately estimates the rating given to a movie by users or
   critics.
2. Movie Rating Prediction project enables you to explore data
   analysis, preprocessing, feature engineering, and machine
   learning modeling techniques. It provides insights into the factors
   that influence movie ratings and allows you to build a model that
   can estimate the ratings of movies accurately.

Dataset:- https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

Explanation of the Code:
1. Data Loading: Load the movie dataset.
2. Data Preprocessing:
    Convert Year and Duration to numeric and fill missing values with the median.
    Convert Votes to numeric and fill missing values with the median.
    Fill missing values in categorical columns with 'Unknown'.
    Encode categorical variables using OneHotEncoder.
3. Model Building:
    Define features (X) and target variable (y).
    Split the data into training and testing sets.
    Preprocess the data.
    Train a RandomForestRegressor model on the training set.
4. Model Evaluation:
    Make predictions on the test set.
    Evaluate the model's performance using Root Mean Squared Error (RMSE) and R^2 Score.
