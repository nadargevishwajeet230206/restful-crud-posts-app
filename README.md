# Express RESTful CRUD Posts App

This is a simple RESTful CRUD application built using Node.js, Express, and EJS.

The project demonstrates how REST APIs work using routes for creating, reading, updating, and deleting posts.

## Features

- View all posts
- Create a new post
- View post details
- Edit a post
- Delete a post

## Technologies Used

- Node.js
- Express.js
- EJS
- Method Override
- UUID

## Routes

GET /posts → display all posts

GET /posts/new → form to create a new post

POST /posts → create a new post

GET /posts/:id → view a single post

GET /posts/:id/edit → edit a post

PATCH /posts/:id → update a post

DELETE /posts/:id → delete a post

## Installation

1. Clone the repository

2. Install dependencies

npm install

3. Start the server

node index.js

4. Open in browser

http://localhost:8080/posts