# ANN-Final-project
This repository contains the code for the project "Clustering and Topic Modeling of Movie Review ", which analyzes movie reviews to group them into meaningful clusters and identify hidden themes using topic modeling techniques.

* Project Overview
The project focuses on:
- Clustering movie reviews based on semantic similarity using Sentence-BERT embeddings.
- Identifying meaningful topics within the clusters using Latent Dirichlet Allocation (LDA) and BERTopic.

* Dependencies
Ensure the following dependencies are installed before running the code:
!pip install kneed
!pip install spacy
!python -m spacy download en_core_web_sm
!pip install bertopic
!pip install pyLDAvis

* Dataset:
The dataset used is the Rotten Tomatoes Movies and Critic Reviews dataset, which contains critic reviews of movies.
Download the dataset from Kaggle 
https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset
