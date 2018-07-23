---
layout: project
type: project
image: images/dataset-original.png
title: Anime Recommender System
permalink: projects/AnimeRec
# All dates must be YYYY-MM-DD format!
date: 2018-05-10
labels:
  - Python
  - Surprise
  - Jupyter
  - Rank
  - Recommender System
summary: Collaborative Based Recommender System for Personalized Anime Recommendations
---

<img class="ui medium right floated rounded image" src="../images/recQualityPlot3.png">

The goal of this project was to develop a __collaborative-based anime recommender system__ capable of generating a __personalized list of unique and relevent anime recommendations__ based on database information comprising total user history and rating ID user feedback.The source of the data is from Kaggle.com [(Anime dataset from Kaggle)](https://www.kaggle.com/CooperUnion/anime-recommendations-database). There are two associated datasets, rating dataset and anime dataset. The rating dataset contains 7,813,737 Ratings (Rating scale: 1- 10) from 73,516 users on 12,294 anime with a density of 0.92%; the anime dataset consists of information about each anime with 7 columns (anime_id, name, genre, type, episodes, rating, and members). Using python with SUPRISE package and leveraging custom built data cleaning and model evaluation programs, I investigated different kinds of __collaborative filtering (CF) algorithms including item-based KNNWithMeans, SVD, Co-clustering, and SVDpp__.  
 
You can learn more about the results and codes at my [GitHub Portfolio](https://github.com/JasonWu1211/Portfolio/tree/master/Anime%20Recommender%20Systems%20%7C%20Python).
