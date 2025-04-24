# VAE-Based Movie Recommender System 

This project implements a **Variational Autoencoder (VAE)** for generating movie recommendations using the **MovieLens dataset**.

## Key Features:
- Achieved **Recall@20: 0.89** and **NDCG@100: 0.86**.
- Generates **top-N recommendations** while masking previous interactions.
- Includes **hyperparameter tuning** (latent dimensions, batch size, epochs).

## How to Run:
1. Load the dataset (`movies.csv` and `ratings.csv`) from https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset.
2. Train the VAE or load pre-trained weights.
3. Evaluate metrics and generate recommendations.

This project was developed referencing the paper https://arxiv.org/abs/1808.01006
