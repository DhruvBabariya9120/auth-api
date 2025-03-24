# Authentication API

A simple Express.js API with signup and login routes, including Swagger documentation.

## Prerequisites

- Node.js
- MongoDB (running locally on port 27017)

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

## API Documentation

Access the Swagger documentation at: http://localhost:3000/api-docs

## Available Routes

- POST /signup - Register a new user
- POST /login - Login with existing credentials

## Request Examples

### Signup
```bash
POST http://localhost:3000/signup
Content-Type: application/json

{
    "email": "user@example.com",
    "password": "yourpassword"
}
```

### Login
```bash
POST http://localhost:3000/login
Content-Type: application/json

{
    "email": "user@example.com",
    "password": "yourpassword"
}
```
