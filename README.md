# React popCorn App

popCorn is a React application that allows users to search for movies,
view detailed information, and manage a list of watched movies.
The app provides functionality to add movies to a watched list, rate them,
and view summaries of the movies.

![popCorn-1](https://github.com/user-attachments/assets/fe2337c5-0c82-4e54-a138-e879aa07191b)

![popCorn-2](https://github.com/user-attachments/assets/504b384f-c49d-40c6-8f67-197a16931a0c)

## Features

- **Search Movies**: Search for movies by title using the search bar(minimum length:3).
- **View Movie Details**: Click on a movie to view details including rating, plot, and actors.
- **Manage Watched Movies**: Add movies to the watched list, rate them, or remove movies from the list.
- **Error Handling**: Displays error messages if movie data fails to load.
- **Responsive Design**: Adapts to various screen sizes.

## Technologies

- **React**: For building the user interface.
- **Custom Hooks**: `useKey`, `useLocalStorageState`, and `useMovies` for managing functionality.
- **CSS**: For styling the application.

## Installation

1. **Clone the Repository**

   `git clone https://github.com/Bzkrtayse/react-popCorn.git`

2. Navigate to the project directory:

   `cd react-popCorn`

3. Install dependencies:

   `npm install`

## Usage

1. Get an API Key

To fetch movie data, you need an API key from the OMDb API. Follow these steps to get your API key:

- Go to OMDb API.
- Sign up for a free or paid plan.
- Once registered, you will receive an API key.
- Add the API Key

Open App.js and replace the KEY variable with your OMDb API key.(line:10)

2. Start the development server:

   `npm start`

3. Open your browser and navigate to `http://localhost:3000`.

