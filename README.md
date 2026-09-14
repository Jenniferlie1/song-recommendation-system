# Content-Based Song Recommendation System
Exploratory data analysis and a content-based recommendation engine built on song audio-feature data.
## Overview
- Dataset: 4,999 rows × 19 columns (song attributes: Key, Mode, Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Artist Genres, etc.)
- Cleaned duplicates, inconsistent values, and missing values
- Categorical audio features (e.g. Key) one-hot encoded to avoid misleading numeric distance calculations
## Workflow
1. EDA — insights and irregularities in the raw dataset, addressed appropriately
2. Data Cleaning — deduplication, inconsistent value handling, missing value imputation, encoding
3. Recommendation Function — content-based system that takes a text input and returns 5 suggested songs
4. Testing — recommendations examined against 3+ different inputs
5. Conclusion
## Tech Stack
Python Pandas NumPy scikit-learn Matplotlib
## Data
song_recomendation_B.csv
