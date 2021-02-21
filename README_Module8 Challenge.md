# Written Analysis of the Movies-ETL challenge Module 8

## Overview of Analysis
For the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data, to perform the appropriate transformations and loads the data into an existing PostgreSQL database.

Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv

## Deliverable/Results: This analysis consists of four technical analysis deliverables:

Deliverable 1: Write an ETL Function to Read Three Data Files
https://github.com/archinarula/Movies-ETL/blob/main/ETL_function_test.ipynb

Deliverable 2: Extract and Transform the Wikipedia Data
https://github.com/archinarula/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb

Deliverable 3: Extract and Transform the Kaggle data
https://github.com/archinarula/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb

Deliverable 4: Create the Movie Database
https://github.com/archinarula/Movies-ETL/blob/main/ETL_create_database.ipynb


## Results

A total of 6052 movies are imported into the database and raw data for the ratings is also added (totalling 26,024,289 ratings across all movies) as proven by the below queries

!https://github.com/archinarula/Movies-ETL/blob/main/Resources/movies_query.png

[!(/Resources/ratings_query.png)]



