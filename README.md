# RoboFriends Search App

Welcome to the **RoboFriends Search App**, a simple interactive project showcasing a search bar functionality that dynamically filters and displays robot cards.

## Project Overview

This repository contains a React application that lets you search and interactively see robot cards. The robots are fetched from [JSONPlaceholder](https://jsonplaceholder.typicode.com/users) API and displayed in an engaging and user-friendly manner.

## Demo

App deployed using Render.com [here](https://robofriends-search-app.onrender.com/)

## Features

- **Search Functionality:** Use the search bar to filter robot cards based on their names. The cards update in real-time as you type.

- **Robot Cards:** Each robot is represented by a card that displays their name, email, and a unique image generated using the [Robohash](https://robohash.org/) service.

- **Responsive Styling:** The application is styled using the lightweight CSS framework [Tachyons](https://tachyons.io/), ensuring a clean and responsive design.

## Project Structure

- `App.js`: The main application component containing the search bar, card list, and scrolling functionality.

- `Card.js`: A component that defines the structure of an individual robot card.

- `SearchBox.js`: A component responsible for rendering the search bar.

- `Scroll.js`: A higher-order component (HOC) that adds a scrollable container to the card list.
