# CineSeek API Documentation Summary

## API Overview
The MoviesDatabase API provides access to a large catalog of movies, including titles, release years, genres, ratings, and more. It supports filtering by year, genre, and sorting results.

## Version
v1

## Available Endpoints
- **GET /titles** — Fetch movies with filters like year or genre  
- **GET /titles/{id}** — Fetch details for a specific movie  
- **GET /titles/search/title** — Search movies by title  
- **GET /titles/series** — Retrieve TV series information

## Request and Response Format
### Example Request:
```bash
GET https://moviesdatabase.p.rapidapi.com/titles?year=2023&genre=Action
