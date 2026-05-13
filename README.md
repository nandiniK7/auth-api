# Auth API

JWT Authentication API built using Node.js, Express.js, MongoDB Atlas, and JWT.

## Features

* User Registration
* User Login
* JWT Token Authentication
* Protected Profile Route
* MongoDB Atlas Database Integration
* REST API using Express.js

## Tech Stack

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT
* bcryptjs
* Postman

## API Endpoints

### Register User

POST /api/users/register

### Login User

POST /api/users/login

### Get Profile (Protected Route)

GET /api/users/profile

## Installation

```bash
npm install
npm run dev
```

## Environment Variables

Create a `.env` file and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=mysecretkey
```

## Postman Documentation

[View Postman Documentation](https://documenter.getpostman.com/view/51232224/2sBXqQEd1r)

## Author

Nandini Kasiraju
