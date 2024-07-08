# AIoT Project - Recommendation System

## Overview
This project focuses on developing a recommendation system as part of the AIoT internship at Harpy Aerospace. The system utilizes collaborative filtering techniques to provide personalized movie recommendations based on user ratings.

## Table of Contents
- [Project Title](#project-title)
- [Author Information](#author-information)
- [Dataset](#dataset)
- [Models](#models)
  - [Collaborative Filtering using k-Nearest Neighbors (k-NN)](#model-1-collaborative-filtering-using-k-nearest-neighbors-knn)
  - [Collaborative Filtering using Matrix Factorization](#model-2-collaborative-filtering-using-matrix-factorization)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)

## Project Title
**Recommendation System**

## Author Information
- **Name:** Gowtham Rajasekaran
- **Institution:** Madras Institute of Technology, AU
- **Student ID:** 20225056084
- **Course:** B.Tech. Information Technology
- **Date:** 07/04/2024

## Dataset
The dataset used in this project is the [MovieLens 100K dataset](http://files.grouplens.org/datasets/movielens/ml-100k.zip). It contains 100,000 ratings from 943 users on 1,682 movies.

## Models

### Model 1: Collaborative Filtering using k-Nearest Neighbors (k-NN)
This model employs the k-NN algorithm to identify similar users and provide recommendations based on their ratings.

*Source Code available in cf model(k-NN).txt* 

### Model 2: Collaborative Filtering using Matrix Factorization
This model uses matrix factorization techniques to decompose the user-item interaction matrix into latent factors for users and items.

*Source Code available in cf model(Matrix Factorisation).txt* 

### Model 3: Graph Neural Network
This model uses matrix factorization techniques to decompose the user-item interaction matrix into latent factors for users and items.

*Source Code available in gnn model.txt* 

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url
   cd your-repo-url
   ```
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter Notebook to execute the models and generate recommendations.
2. Follow the instructions in the notebook to train the models and make predictions.

## Results
The models provide personalized movie recommendations based on user ratings. The performance of each model is evaluated using appropriate metrics.

## Visualization
The project includes visualizations for:
- Distribution of ratings
- Top recommendations for selected users

