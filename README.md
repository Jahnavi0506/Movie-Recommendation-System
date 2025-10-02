✅ Project Overview

A Python-based movie recommendation system that suggests similar movies using metadata and cosine similarity.

✅ Technologies Used

Python

Pandas / NumPy

Scikit-learn

difflib

✅ Dataset

Make sure your CSV file (e.g., movies.csv) has the following columns:

title, index, genres, keywords, tagline, cast, director

✅ How It Works

Load the dataset

Handle missing values

Combine selected text features

Vectorize the text using TF-IDF

Compute cosine similarity scores

Match user input to closest movie title

Recommend top similar movies

✅ How to Run
1. Place movies.csv in your working directory
2. Run the Python script (or use a Jupyter Notebook)
3. When prompted, enter a movie name:
   ➜ Enter your favourite movie name:
4. Get top 25 similar movie suggestions.

✅ Example Output
Movies Suggested for you:
1 - The Avengers
2 - Iron Man 2
3 - Captain America: Civil War
......
