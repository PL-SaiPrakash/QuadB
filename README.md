# React Native Movie App

## Overview

This project is a React Native app designed to display movie information. It includes a splash screen, home screen, search screen, and details screen.

## Screens

### Splash Screen

- Contains an introductory image related to the app theme.
- Displayed briefly before navigating to the home screen.

### Home Screen

- Displays a list of movies fetched from the API endpoint: [TVMaze API - Search Shows](https://api.tvmaze.com/search/shows?q=all).
- Each movie is presented with a thumbnail image, title, and summary.
- Tapping on a movie navigates to the Details Screen.
- Includes a Home and search options at  bottom.

### Search Screen

- Features a search bar allowing users to search for movies.
- Searches are performed using the API endpoint: [TVMaze API - Search Shows](https://api.tvmaze.com/search/shows?q=${search_term}).
- Displays search results in the same format as the Home Screen.

### Details Screen

- Shows detailed information about the selected movie including:
  - Thumbnail image
  - Title
  - Summary
  - Additional movie details

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/PL-SaiPrakash/QuadB.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd QuadB
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Start the development server:**

    ```bash
    npm start
    ```





Thank you for checking out this project!
