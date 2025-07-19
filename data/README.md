# 📁 Data Folder

This folder contains the dataset used in the Spotify Popularity Analysis project.

## Contents

- `dataset_Spotify.csv`  
  This is the **raw dataset** containing metadata and audio features of Spotify tracks.  
  The data includes attributes such as track name, artist, release year, danceability, energy, acousticness, popularity score, and more.

## Notes
- The file is **not cleaned or preprocessed**. All analysis, feature engineering, and transformations are applied within the main notebook (`spotify_data_analytics.ipynb`).
- File encoding is UTF-8. Missing values and outliers are handled during the preprocessing stage.
- The dataset may contain tracks from multiple genres and years, providing a wide range of variability for predictive modeling.

## Source
- https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
