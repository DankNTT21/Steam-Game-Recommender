Link to Dataset: https://www.kaggle.com/datasets/artermiloff/steam-games-dataset

# Unsupervised Steam Game Recommender

This is a content-based game recommender using **unsupervised learning**. It recommends similar games based on genres using TF-IDF feature extraction and cosine similarity.

## How it Works
1. Load the dataset (name and genres of games).
2. Preprocess missing values.
3. Convert genres into numeric vectors using TF-IDF.
4. Compute similarity of the input game to all other games.
5. Return top 5 most similar games.

## Usage (Replace "Hades" With Any Game You Want)
```python
from game_recommender import recommend_games_safe

recommend_games_safe("Hades")
