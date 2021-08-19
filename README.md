# Music-Genre-Classification-challenge
# 3rd Rank solution

## Overview

Music has been an important part of our lives since time immemorial. Every artist has a signature, making music a subjective art. We have scales/metrics to measure the quality of music. But, is it possible to train a machine learning model to predict the genre and quality of the music?

Currently, many music aggregator applications rely on machine learning to power their recommendation engine, and curate playlists. MachineHack is challenging data scientists and machine learning practitioners to build a highly scalable ML model for a music aggregator app (Company ABC) to accurately predict the genre of songs in the dataset.

## About Dataset

#### Training dataset: 
17,996 rows with 17 columns 

#### Column details: 
artist name; track name; popularity; ‘danceability’; energy; key; loudness; mode; ‘speechiness’; ‘acousticness’; ‘instrumentalness’; liveness; valence; tempo; duration in milliseconds and time_signature. 

#### Target Variable: 
'Class’ such as Rock, Indie, Alt, Pop, Metal, HipHop, Alt_Music, Blues, Acoustic/Folk, Instrumental, Country, Bollywood, 

#### Test dataset: 
7,713 rows with 16 columns 

## Evaluation

### What is the Metric In this competition? How is the Leaderboard Calculated ?

- The submission will be evaluated using the **Log Loss metric**. One can use sklearn.metric.log_loss to calculate the same
- This hackathon supports private and public leaderboards
- The public leaderboard is evaluated on 30% of Test data
- The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% Test data
