# 🎥 Movie Library - Full Stack MERN Application

A dynamic and user-friendly full stack Movie Library application built with **React** on the frontend and **Node.js/Express** on the backend. It features secure authentication, robust movie and genre management, and a review system.

---

## ✨ Features

### 🎬 Movie Management

* Create, edit, delete, and view movies
* Fetch latest, top-rated, and random movies
* Submit and delete movie reviews

### 🎭 Genre Management

* Add, update, delete, and list movie genres

### 👤 User Management

* Secure registration and login with hashed passwords
* JWT-based authentication with cookie-based tokens
* Profile view and update
* Logout functionality

---

## 🧰 Tech Stack

| Frontend     | Backend      | Database | Authentication |
| ------------ | ------------ | -------- | -------------- |
| React        | Node.js      | MongoDB  | JWT            |
| Axios        | Express.js   | Mongoose | bcrypt         |
| React Router | RESTful APIs |          | Cookies        |

---

## 🌐 API Overview

### 🎥 Movies

* `POST /api/movies`
* `GET /api/movies`
* `GET /api/movies/:id`
* `PUT /api/movies/:id`
* `DELETE /api/movies/:id`
* `POST /api/movies/:id/review`
* `DELETE /api/movies/comment`
* `GET /api/movies/new`
* `GET /api/movies/top`
* `GET /api/movies/random`

### 🏋️ Genres

* `POST /api/genres`
* `GET /api/genres`
* `GET /api/genres/:id`
* `PUT /api/genres/:id`
* `DELETE /api/genres/:id`

### 👥 Users

* `POST /api/users/register`
* `POST /api/users/login`
* `POST /api/users/logout`
* `GET /api/users/profile`
* `PUT /api/users/profile`
* `GET /api/users` *(Admin only)*

---

## ⚙️ Getting Started

### 📦 Prerequisites

* Node.js & npm
* MongoDB instance (local or cloud)

### 🔧 Backend Setup

```bash
git clone https://github.com/your-username/movie-library.git
cd movie-library
npm install
npm start
```

### 💻 Frontend Setup

```bash
cd client
npm install
npm start
```

---

## 📁 Folder Structure

```
movie-library/
├── controllers/         # Backend logic (User, Movie, Genre)
├── models/              # Mongoose schemas
├── routes/              # Express routes
├── middlewares/         # Middleware (auth, async handler)
├── client/              # React frontend
├── .env                 # Environment variables
├── server.js            # Entry point
```

---

## 📅 Environment Variables

Create a `.env` file in the root directory with the following:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

## 🙌 Acknowledgments

* Inspired by IMDb, TMDB
* Built with ❤️ using React, Node.js, and MongoDB


---

## Acknowledgments

* Inspired by IMDb, TMDB
* Built with ❤️ using Node.js and MongoDB
