# Movie Recommendation System

## Overview

This project implements a Movie Recommendation System using Python. The system analyzes movie data and suggests similar movies based on user input. It utilizes machine learning techniques, particularly the TF-IDF Vectorizer and Cosine Similarity, to identify relationships between movies based on various features.

## Features

- **Data Collection**: The system loads movie data from a CSV file.
- **Preprocessing**: It preprocesses the data by filling missing values and combining relevant features such as genres, keywords, tagline, cast, and director.
- **Similarity Calculation**: It computes similarity scores between movies using the TF-IDF Vectorizer and Cosine Similarity.
- **User Interaction**: Users can input their favorite movie, and the system will return a list of similar movies based on their choice.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Difflib

## How to Use

1. Clone the repository to your local machine.
2. Ensure that you have the required libraries installed.
3. Place the movie data CSV file in the appropriate directory.
4. Run the script to start the recommendation process.
5. Enter the name of your favorite movie when prompted.

