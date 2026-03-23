# User Management System

A RESTful API for user management built with Node.js, Express, and MongoDB.

## Features
- Create, Read, Update, Delete users (CRUD)
- MongoDB database with Mongoose
- Basic Authentication to secure endpoints

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- express-basic-auth

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /users | Create a user |
| GET | /users | Get all users |
| GET | /users/:id | Get single user |
| PUT | /users/:id | Update a user |
| DELETE | /users/:id | Delete a user |

## Authentication
All endpoints are protected with Basic Authentication.
- Username: admin
- Password: password123
