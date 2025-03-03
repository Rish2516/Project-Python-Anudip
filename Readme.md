# Netflix Dataset Analysis

## Overview
This repository contains a dataset of Netflix shows and movies, along with analyses performed on the data. The dataset includes various attributes such as show ID, type, title, director, cast, country, date added, release year, rating, duration, listed genres, and description.

## Dataset Description
The dataset consists of the following columns:
- **show_id**: Unique identifier for each show/movie
- **type**: Type of content (Movie or TV Show)
- **title**: Title of the show/movie
- **director**: Director of the show/movie
- **cast**: Cast of the show/movie
- **country**: Country of production
- **date_added**: Date the show/movie was added to Netflix
- **release_year**: Year the show/movie was released
- **rating**: Rating of the show/movie
- **duration**: Duration of the movie or number of seasons for TV shows
- **listed_in**: Genres of the show/movie
- **description**: Description of the show/movie

## Data Cleaning Process
The data cleaning process involved:
- Handling missing values by replacing them with appropriate defaults (e.g., "Unknown" for director and cast)
- Filling missing values in the 'country', 'date_added', and 'rating' columns with the most frequent values
- Removing duplicates from the dataset
- Saving the cleaned dataset as `cleaned_netflix_database_Anudip.csv`

## Data Analysis
The analysis performed on the cleaned dataset includes:
- Count of different types of shows (movies vs. TV shows)
- Identification of the most and second most frequent directors
- Total, average, maximum, and minimum durations of movies
- Counts of productions by country
- Counts of releases by date and year
- Analysis of descriptions containing specific keywords (e.g., "murder", "comedy", "love")

## How to Use
1. Clone the repository.
2. Ensure you have the required libraries installed (e.g., pandas, numpy, matplotlib).
3. Run the Jupyter notebooks to perform data cleaning and analysis.

## License
This project is licensed under the MIT License.
