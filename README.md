# mlzoomcamp-2022-CapstoneProject-Music-Genre

This is a Capstone project for ML Zoomcamp 2022 (TODO: classify music  into genres)

## Problem description

This is a classification problem. We classify music into 10 genres, using different audio features 
such as acousticness, danceability, duration_ms, energy, instrumentalness, 
liveness, loudness, mode, popularity, speechiness, tempo, valence.

For solve this problem we use different models for multiclass classification such as Random Forest, XGBoost
 and KNeighbors.

## Dataset

This project based on [Prediction of music genre] 
(https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre). 
The full list of genres included in the CSV are 'Electronic', 'Anime', 'Jazz', 'Alternative', 
'Country', 'Rap', 'Blues', 'Rock', 'Classical', 'Hip-Hop'.
Set of audio features provided by Spotify.

## Descriptions

Project folder contains

* data
* images
* models
* notebooks
  * MusicGenreEDA+DataPreparation.ipynb
  * Music_genre_model_training_and_data_preparation
  * Music_Genre_predict.ipynb
* src
* Dockerfile
* Pipfile
* Pipfile.lock
* Predict.py
* Readme.md