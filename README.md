# Spotify Popularity Prediction

A machine learning project that predicts Spotify track popularity using audio features and regression models.

## Overview

This project develops and evaluates machine learning models to predict Spotify track popularity using audio characteristics from over 80,000 songs.

## Dataset

- 80,000+ Spotify tracks
- Audio features and popularity score

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Machine Learning Workflow

- Data cleaning
- Feature engineering
- Exploratory Data Analysis (EDA)
- Cross-validation
- Hyperparameter tuning
- Model evaluation

## Models

- K-Nearest Neighbors Regression
- Random Forest Regression

## Results

- Random Forest achieved a test **R² ≈ 0.40**
- **RMSE ≈ 15.1**
- Feature importance analysis identified instrumentalness, loudness, energy, duration, and acousticness as key predictors of track popularity.

## Repository Structure

```
Spotify_Popularity_Prediction.ipynb   # Main notebook
dataset.csv                           # Dataset
```
