Steam-Game-Recommender:

This is a simple game recommender system built in Python using content-based filtering.

How it Works
1. Loads a CSV file containing game names and genres.
2. Converts genres into numeric vectors using TF-IDF.
3. Calculates similarity between games using cosine similarity.
4. Returns the top 5 games most similar to a chosen game.

Usage:
(Replace "Hades" with any game name to get recommendations.)
```python

from game_recommender import recommend_games_lazy_safe

recommend_games_lazy_safe("Hades")
