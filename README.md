## Film Zone – React Movie Search App

Film Zone is a React-based web application that allows users to search for movies and view essential details such as the movie poster, release year, and type. The app fetches real-time movie data from the OMDb API and displays the results in a clean, responsive card-based UI.

This project was built to practice and demonstrate core React concepts including components, props, state management, hooks, and API integration.

## Features

-Search movies by title

-Fetch real-time movie data using the OMDb API

-Display movie poster, title, year, and type

-Reusable React components

-Responsive and modern UI design

-Fast and lightweight application

## Tech Stack

Frontend: React.js

Language: JavaScript (ES6)

Styling: CSS3

API: OMDb API

Tools: Create React App, Fetch API

## Project Structure
src/
├── App.js
├── App.css
├── MovieCard.jsx
├── search.svg
└── index.js

## Screenshots


## Installation & Setup

Follow the steps below to run the project locally:

1. Clone the repository
git clone https://github.com/your-username/film-zone.git

2. Navigate to the project directory
cd film-zone

3. Install dependencies
npm install

4. Start the development server
npm start


5. The application will run at:
 http://localhost:3000

## API Used

OMDb API
Website: https://www.omdbapi.com/

The OMDb API is used to retrieve movie data based on the search query entered by the user.

## How the Application Works

On initial load, the app fetches movies related to "Batman".

The user enters a movie name in the search bar.

A request is sent to the OMDb API with the search term.

The response data is stored in the application state.

Movie results are rendered dynamically as movie cards.

## Learning Outcomes

Building applications using React functional components

Using useState and useEffect hooks

Fetching and handling external API data

Passing data between components using props

Conditional rendering in React

Designing responsive layouts using CSS

## Notes

This project was created for learning and practice purposes.

The concept and API usage are inspired by common React tutorial projects.

Not intended for production deployment.

## Future Enhancements

Add loading and error handling states

Display detailed movie information on card click

Add pagination for search results

Improve UI animations and transitions

Secure the API key using environment variables

## Author

Film Zone
GitHub: https://github.com/linittaelezabath

## Acknowledgements

OMDb API for providing movie data

React documentation and community tutorials
