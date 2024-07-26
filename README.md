# Data Sourcing Challenge

## Overview

This project extracts and merges movie data from two different APIs: The New York Times API and The Movie Database API. The goal is to prepare this data for future use in a recommendation system and natural language processing tasks.

## What the Code Does

1. **API Data Extraction**:
   - Accesses the New York Times API to retrieve movie reviews and related articles.
   - Accesses The Movie Database API to fetch detailed movie information.

2. **Data Merging**:
   - Merges the data from both APIs into a single DataFrame based on movie titles.

3. **Data Cleaning**:
   - Removes duplicates and irrelevant data.
   - Ensures the data is in a consistent format for further analysis.

4. **Exporting Data**:
   - Exports the cleaned and merged data to a CSV file for use in future projects.

## How to Run the Code

1. **Setup**:
   - Add your API keys to the `.env` file (rename `example.env` to `.env`).
   - Ensure you have the required dependencies installed.

2. **Execution**:
   - Run the `retrieve_movie_data.ipynb` Jupyter notebook to perform data extraction, merging, and cleaning.
   - The final cleaned data will be exported to a CSV file.

## Conclusion

This project demonstrates how to extract, merge, and clean movie data from multiple APIs, preparing it for further analysis and application in a recommendation system.