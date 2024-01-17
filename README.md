# React Movie DB App

Welcome to the React Movie DB App! This React application allows users to search for movies using the OMDb API. Users can explore a collection of movies, view details for each movie, and navigate through the app seamlessly.

## Live Demo

Explore the live demo: [React Movie DB App](https://react-movie-db1.netlify.app/)

## Overview

The React Movie DB App uses the OMDb API to fetch and display information about movies. Users can enter search queries to find movies, and the app provides a list of results. Individual movie details, such as the poster, title, and release year, are displayed for users to explore.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Avinash9694/React-Movie-DB-App.git
   cd React-Movie-DB-App
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Obtain OMDb API Key:

   - Create an account on OMDb (https://www.omdbapi.com/apikey.aspx) to obtain your API key.

4. Create a `.env` file in the project root directory and add your OMDb API key:

   ```
   REACT_APP_MOVIE_API_KEY=your_api_key_here
   ```

5. Run the project:

   ```bash
   npm start
   ```

Visit [http://localhost:3000](http://localhost:3000) in your browser to explore the React Movie DB App.

## Features

- **Movie Search:** Enter search queries to fetch and display relevant movie information.
- **Movie Details:** View detailed information about each movie, including the poster, title, and release year.

## Components

- **App.js:** Main React component managing the app's routes.
- **Home.js:** React component rendering the movie search form and list of movies.
- **Movie.js:** React component displaying details for a single movie.
- **NotFound.js:** React component rendered when a route is not found.
- **SearchForm.js:** React component providing the movie search form.

## Context

- **context.js:** Context provider managing the app's state, including movie data, loading status, and search queries.
- **Movies.js:** React component displaying a list of movies fetched from the OMDb API.
- **SearchForm.js:** React component providing the movie search form.

## API Integration

The project integrates with the OMDb API to fetch and display movie information. The API key is required for authentication.
