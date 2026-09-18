# Anime Recommendation System using NCF and Knowledge Graph

## Overview
A personalized anime recommendation system built using Neural Collaborative Filtering (NCF) and enhanced with Knowledge Graph embeddings to improve recommendation relevance and reduce the cold-start problem.

## Features
- Personalized recommendations using NCF
- Knowledge Graph-based anime embeddings
- User–Anime interaction modeling
- Genre and type relationship learning
- Top-N anime recommendation function

## Dataset
- Anime dataset
- User ratings dataset
- Source: Kaggle

## Technologies
Python, TensorFlow, Keras, Pandas, NumPy, NetworkX, PyKEEN, Scikit-learn

## Model Architecture
User ID + Anime ID → Embedding → Concatenate → Dense Layers → Rating Prediction

## Results
- Reduced recommendation error using KG-enhanced embeddings
- Improved relevance for new or sparsely rated anime
