# NTI E-Learn Backend

NTI E-Learn is a backend RESTful API for an e-learning platform designed to manage users, courses, and learning resources.
The project provides a scalable server-side architecture that supports authentication, course management, and structured API development using modern backend practices.

## Features

* User authentication and authorization
* Course and learning content management
* RESTful API architecture
* Structured backend using Node.js and Express
* Modular project structure for scalable development

## Tech Stack

* Node.js
* Express.js
* JavaScript (ES Modules)
* REST API
* MongoDB

## Project Structure

src/
modules/
controllers/
services/
routes/

index.js
package.json

The application follows a modular architecture separating routes, controllers, and business logic to maintain clean and maintainable code.

## API Endpoints

POST /auth/register
POST /auth/login
GET /courses
POST /courses
GET /users

## Environment Variables

Create a `.env` file in the root directory and add the following variables:

PORT=
DB_URI=
JWT_SECRET=

## Purpose

This project was developed as part of backend training to practice building scalable APIs and implementing real-world backend architecture using Node.js and Express.
