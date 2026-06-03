# Movie Recommendation System

## Project Overview

This project is a Movie Recommendation System developed using Python and Machine Learning. It recommends movies similar to a selected movie based on user ratings and movie similarity.

The system uses the MovieLens dataset and collaborative filtering techniques to generate personalized movie recommendations.

## Features

* Recommends movies based on user preferences
* Uses movie ratings to identify similar movies
* Calculates similarity using Cosine Similarity
* Generates top movie recommendations
* Simple and efficient recommendation engine

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses the MovieLens dataset.

Files Used:

* movies.csv
* ratings.csv

Dataset Information:

* Movie titles and genres
* User ratings for movies
* Thousands of movie-rating records

## Project Workflow

### 1. Data Collection

Load movie and rating datasets.

### 2. Data Preprocessing

* Handle missing values
* Create a user-movie rating matrix
* Prepare data for similarity calculations

### 3. Similarity Calculation

* Use Cosine Similarity to measure movie similarity
* Identify movies with similar rating patterns

### 4. Recommendation Generation

* Select a movie title
* Find similar movies
* Display top recommendations

## Installation

Install required libraries:

pip install pandas numpy scikit-learn

## Running the Project

1. Download the MovieLens dataset.
2. Place `movies.csv` and `ratings.csv` in the project folder.
3. Open `movie_recommendation.ipynb`.
4. Run all cells.

## Sample Output

Input Movie:
Toy Story (1995)

Recommended Movies:

* Toy Story 2 (1999)
* Monsters, Inc. (2001)
* Finding Nemo (2003)
* A Bug's Life (1998)
* Shrek (2001)

## Future Improvements

* Add genre-based recommendations
* Build a web application using Streamlit
* Improve recommendations using advanced collaborative filtering techniques
* Add user authentication and profiles

## Conclusion

This project demonstrates how machine learning can be used to build recommendation systems that help users discover movies based on their interests and viewing patterns.

## Author

Bellaganti Harika

## License

This project is developed for educational and internship purposes.
