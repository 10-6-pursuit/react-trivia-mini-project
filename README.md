# React Trivia Game Project Instructions

## Overview

In this project, you will build a trivia game using React and the Open Trivia Database API. The game will allow users to select different options for the type of questions they want to play with. Upon submission, the game will fetch questions from the API based on the selected options. Additionally, you will implement routing for the home page, about me, form, and trivia game.

## Project Requirements

1. Set up a new React project using Create React App or your preferred method.
2. Create separate components for the home page, about me, form, and trivia game.
3. Implement routing using React Router to navigate between different views/pages.
4. Integrate a form component to capture user preferences for the trivia game options.
5. Use the `fetch` API or a library like Axios to send requests to the Open Trivia Database API and retrieve questions based on user preferences.
6. Display the fetched questions and answer options to the user in the trivia game component.
7. Style the project to your liking.

## Step-by-Step Instructions

### 1. Setting up the React Project

Start by creating a new React project using Vite

### 2. Installing Dependencies

Install React Router for navigation:

```bash
npm install react-router-dom
```

### 3. Creating Components

Create separate components for the home page, about me, form, and trivia game. You can structure your components as follows:

- `HomePage.jsx`
- `AboutMe.jsx`
- `Form.jsx`
- `TriviaGame.jsx`

### 4. Implementing Routing

Set up routing using React Router in your `App.js` file. Define routes for each component

### 5. Implementing Form Component

Create a form component (`Form.js`) to capture user preferences for the trivia game options. Include input fields for the number of questions, category, difficulty, and type.

### 6. Fetching Questions from the API

Write JavaScript code to handle form submission in the form component (`Form.js`). Use Axios to send requests to the Open Trivia Database API with the user-selected options.

### 7. Displaying Questions to the User

Render the fetched questions and answer options in the trivia game component (`TriviaGame.js`). Allow users to play the trivia game by selecting answers and navigating through questions.

## Additional Notes

- Ensure error handling in case the API request fails or returns an error response.
- Provide appropriate feedback to the user during the loading process (e.g., loading spinner, progress bar).
- Style your components using CSS or a CSS framework like Bootstrap to enhance the user experience.

## Query String Options

Here are the available options for the query string when constructing the API request:

- `amount`: (integer) Number of questions (default: 10).
- `category`: (integer) Category ID (Refer to the [API documentation](https://opentdb.com/api_config.php) for category IDs).
- `difficulty`: (string) Difficulty level (easy, medium, hard).
- `type`: (string) Type of questions (multiple, boolean).

Refer to the [API documentation](https://opentdb.com/api_config.php) for more details on query parameters and their possible values.
