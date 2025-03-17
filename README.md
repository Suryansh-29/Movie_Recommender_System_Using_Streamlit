
# Movie Recommendation System

## Overview
This project is a Movie Recommendation System that suggests movies based on user preferences. It uses a content-based filtering approach to recommend movies similar to the one selected by the user. The system leverages the TMDB (The Movie Database) API to fetch movie posters and other relevant details.

## Features
- **Content-Based Filtering**: The system recommends movies based on the similarity of their content, such as genres, keywords, cast, and crew.
- **Interactive Interface**: Built with Streamlit, the system provides an interactive and user-friendly interface.
- **Movie Posters**: The system fetches and displays movie posters using the TMDB API.

## How It Works
1. **Data Collection**: The dataset used in this project contains information about movies, including their titles, genres, keywords, cast, and crew.
2. **Data Preprocessing**: The data is preprocessed to combine relevant features into a single "tags" column, which is then used to compute similarity between movies.
3. **Similarity Calculation**: The system uses cosine similarity to find movies that are most similar to the one selected by the user.
4. **Recommendation**: The top 5 most similar movies are recommended to the user, along with their posters.
