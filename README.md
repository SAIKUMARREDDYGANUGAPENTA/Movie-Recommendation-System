# Movie-Recommendation-System

## Overview

This Movie Recommender System is a Python-based application with a user-friendly Streamlit interface. It suggests movies based on a selected title using a collaborative filtering approach.

## Features

Interactive UI: Streamlit-powered interface for easy user interaction.
Movie Recommendations: Get personalized movie recommendations using collaborative filtering.
Movie Posters: Fetches movie posters from The Movie Database (TMDb) API.


## Setup Instructions

Step 1:Clone the repository to your local machine.
           git clone https://github.com/yourusername/movie-recommender.git

Step 2: Navigate to the project directory.
          cd movie-recommender

Step 3:Install the required dependencies.
         pip install streamlit requests pandas

Step 4:Run the Streamlit application.
         streamlit run app.py

The application will be accessible at http://localhost:8501 in your web browser.

## Project Structure

app.py: The main Streamlit application file.
movie_list.pkl: Pickle file containing movie data.
similarity.pkl: Pickle file containing similarity matrix data.

## Usage

Access the application at http://localhost:8501 in your web browser.
Choose a movie from the dropdown menu.
Click the "Show Recommendation" button to see personalized movie suggestions.
View movie names and posters in the displayed columns.

##  Data Sources

The Movie Database (TMDb): Movie information and poster images are fetched using the TMDb API.

## Contributing

Contributions are welcome! If you'd like to enhance or fix issues, please follow these steps:


1.Fork the repository.
2.Create a new branch for your feature or bug fix.
3.Make your changes.
4.Submit a pull request.






