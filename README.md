# Trending Movies App

A full-stack movie discovery application built with React, Tailwind CSS, TMDB API, and Appwrite. The application allows users to search movies in real time, tracks search frequency, and displays trending movies based on user interactions.


# Overview

This project demonstrates real-world frontend and backend integration using modern web technologies. It focuses on performance optimization, clean component architecture, and data-driven features such as search analytics and trending content.


# Features

• Movie search using the TMDB API

• Popular movie discovery when no search query is provided

• Trending movies ranked by user search frequency

• Debounced search to reduce unnecessary API calls

• Loading and error state handling

• Responsive and accessible UI


# Tech Stack
## Frontend

React
Vite
Tailwind CSS

## Backend / Services

TMDB REST API
Appwrite (Database and SDK)

# Architecture and Design Decisions

• Component-based architecture for maintainability and reusability

• Separation of UI, business logic, and external service integration

• Asynchronous data fetching using async/await

• Debounced search input to improve performance and user experience

• Appwrite used as an analytics backend to store and rank search data

• Defensive rendering to safely handle missing or partial API responses


