# Movie-Recommendation-Engine

A Movie Recommendation Engine is developed using the Movie Lens Dataset. The data is available for use as it is an open source dataset. 
Link to Dataset : https://drive.google.com/drive/folders/1JnQXDCsGAb75I4PRRMDHUO0WxmXT-usv

# Dataset

This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
The small dataset: This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
We will build a simple Recommendation for movies using The full dataset.

# Data Description

It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. 
This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. 
No demographic information is included. Each user is represented by an id, and no other information is provided.

The Dataset contains the following files : 

credits.csv
keywords.csv
links.csv
links_small.csv
movies_metadata.csv
ratings.csv
ratings_small.csv


# Dependencies 

pandas
numpy
scipy
scikit-learn
scikit-surprise
lightfm
matplotlib
seaborn
jupyter notebook
jupyter lab
textblob

# Intro_recommendation_system.ipynb

This file explains the logic behind the Recommendation System. It has in depth information about the use of statistical functions that are used to design a basic Recommendation System. 

# Movie_recommendation_engine.ipynb 

This File has the Recommendation System building using simple recommendation, Content Based Recommendation System, CF Based Recommendation System, Hybrid Filtering.

