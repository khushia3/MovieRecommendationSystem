Movie Recommendation System

Overview

This project is a content-based movie recommendation system that suggests similar movies based on textual features. It uses the TDMA database to store movie data and employs TF-IDF vectorization along with cosine similarity to find and recommend movies.

Features

Uses CountVectorizer from sklearn.feature_extraction.text to transform movie descriptions into feature vectors.

Computes cosine similarity between movies to determine closeness.

Provides top-5 movie recommendations based on user input.

Works efficiently with TDMA database for data storage and retrieval.

Technologies Used

Python

Scikit-learn

Pandas

NumPy

TDMA Database

Installation

To run this project locally, follow these steps:

Clone the repository:

git clone (https://github.com/khushia3/MovieRecommendationSystem)

Navigate to the project directory:

cd movie-recommendation-system

Install required dependencies:

pip install -r requirements.txt

Usage

Load the dataset into the TDMA database.

Run the Python script to train the model and generate recommendations:

python main.py

Enter a movie title when prompted to get recommendations.

Code Structure

movie-recommendation-system/
│── data/                     # Folder for storing movie data
│── models/                   # Folder for storing trained models
│── scripts/                  # Python scripts for training and recommendation
│── main.py                   # Entry point for running the recommendation system
│── requirements.txt           # List of required dependencies
│── README.md                  # Project documentation
