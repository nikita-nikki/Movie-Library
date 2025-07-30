# Movie Library - RESTful API

A comprehensive Movie Library backend built with Node.js and Express. It allows users to register, login, and manage a collection of movies, genres, and reviews.

---

## Features

### 🎬 Movie Management

* Add, update, delete, and retrieve movies
* Fetch new, top-rated, and random movies
* Add and delete movie reviews

### 🌐 Genre Management

* Create, update, read, and delete genres
* View all genres

### 👤 User Management

* User registration and login with password hashing
* JWT-based authentication
* Profile management (view/update)
* Logout functionality

---

## Tech Stack

* **Backend:** Node.js, Express
* **Database:** MongoDB
* **Authentication:** JWT (JSON Web Tokens), bcrypt

---

## API Endpoints Overview

### Movies

* `POST /api/movies` - Create a new movie
* `GET /api/movies` - Get all movies
* `GET /api/movies/:id` - Get specific movie
* `PUT /api/movies/:id` - Update movie
* `DELETE /api/movies/:id` - Delete movie
* `POST /api/movies/:id/review` - Add movie review
* `DELETE /api/movies/comment` - Delete movie comment
* `GET /api/movies/new` - Get new movies
* `GET /api/movies/top` - Get top-rated movies
* `GET /api/movies/random` - Get random movies

### Genres

* `POST /api/genres` - Create genre
* `GET /api/genres` - Get all genres
* `GET /api/genres/:id` - Read genre
* `PUT /api/genres/:id` - Update genre
* `DELETE /api/genres/:id` - Delete genre

### Users

* `POST /api/users/register` - Register new user
* `POST /api/users/login` - Login
* `POST /api/users/logout` - Logout
* `GET /api/users/profile` - Get logged-in user profile
* `PUT /api/users/profile` - Update profile
* `GET /api/users` - Get all users (admin)

---

## Getting Started

### Prerequisites

* Node.js
* MongoDB

### Installation

```bash
git clone https://github.com/your-username/movie-library.git
cd movie-library
npm install
```

### Running the Server

```bash
npm start
```

---

## Folder Structure

* `controllers/` - Contains user, movie, and genre controllers
* `models/` - Mongoose models for User, Movie, and Genre
* `middlewares/` - Async handler, authentication, etc.
* `routes/` - API routes

---

## Acknowledgments

* Inspired by IMDb, TMDB
* Built with ❤️ using Node.js and MongoDB
