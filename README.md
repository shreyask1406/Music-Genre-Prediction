
# Music Genre Prediction Based on Audio Features

## Introduction
In the age of hyper-personalization, the music industry is constantly striving to enhance user engagement and provide tailored recommendations. This project focuses on accurately predicting the genre of a song based on its audio features. By leveraging machine learning classification techniques, we aim to identify the genre and explore the impact of various audio attributes on this prediction.

## Problem Definition
The objective of this project is to classify songs into their respective genres using audio features. By processing the dataset and visualizing the distributions of audio features, we build a classification model to accurately predict the genre of a song. The dataset, sourced from Kaggle, contains 18 columns including audio attributes, artist information, and genre labels.

## Data Overview
Dataset: Link to Dataset on Kaggle
Columns: instance_id, artist_name, track_name, popularity, acousticness, danceability, duration_ms, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, obtained_date, valence, music_genre
Genres: 'Electronic', 'Anime', 'Jazz', 'Alternative', 'Country', 'Rap', 'Blues', 'Rock', 'Classical', 'Hip-Hop'
Data Processing and Exploration
We undertook several steps to prepare and understand the data:

## Handling missing values and incorrect data entries
Exploring the distribution of audio features across genres
Identifying correlations between features and genres
Feature Selection
Based on the data exploration and analysis, we decided to focus on the following audio features for modeling: Popularity, Danceability, Energy, Liveness, Loudness, Tempo, and Valence. These features demonstrated a significant impact on genre prediction.

## Classification Models
We explored several classification algorithms to predict genres:
* Decision Trees
* K-Nearest Neighbors (KNN)
* Random Forest
* Logistic Regression
* Support Vector Machine (SVM)

## Model Performance
We iteratively improved the models by:
* Eliminating low-impact features
* Applying feature selection techniques
* Grouping similar genres together

The final models achieved impressive accuracy scores:
* Decision Trees: 84.38%
* KNN: 84.59%
* Random Forest: 87.58%
* Logistic Regression: 82.17%
* SVM: 86.83%
  
## Conclusion
This project showcases the power of audio features in predicting music genres. By leveraging machine learning techniques, we successfully built accurate models for genre classification. The README provides a concise overview of the project, data processing steps, model exploration, and final results.

Feel free to explore the code and further insights in the accompanying files!
