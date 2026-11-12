# Flavorly – Recipe App

A recipe discovery web application built with React that allows users to explore recipes, view cooking instructions, and save their favourite recipes.

## Features

- Browse a variety of recipes.
- Search recipes by name.
- View detailed recipe information.
- Display ingredients and cooking instructions.
- Save and remove favourite recipes.
- Persist favourite recipes using localStorage.
- Navigate between pages using React Router.
- Loading and error handling for API requests.

## Technologies

- React.js
- JavaScript
- HTML5
- CSS3
- React Router
- Axios
- React Hooks
- TheMealDB API
- Vite

## Project Structure

```text
Flavorly/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── hooks/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
└── README.md
```

## Installation

Install the project dependencies:

```bash
npm install
```

## Run the Project

Start the development server:

```bash
npm run dev
```

Open the local URL provided by Vite in your browser.

## Application Pages

- Home – Discover recipes.
- Recipes – Browse and search recipes.
- Recipe Details – View ingredients and cooking instructions.
- Favourites – Access and manage saved recipes.

## API Integration

Recipe data is fetched from TheMealDB API using Axios.

## Data Storage

Favourite recipes are stored in localStorage and remain saved across page refreshes.
