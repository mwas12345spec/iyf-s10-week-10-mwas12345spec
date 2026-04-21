# Week 10: CommunityHub Backend API

## Author
- **Name:** Mark  Mwangi
- **GitHub:** mwas12345spec  
- **Date:** April 21, 2026

## Project Description

This project is a backend REST API for CommunityHub built using Node.js and Express.

The goal of this project was to learn backend fundamentals by building a server, creating routes, 
implementing CRUD operations, using middleware, handling errors, organizing code into modules, and
working with environment variables.

The API allows users to:

- Create posts  
- View all posts  
- View a single post  
- Update posts  
- Delete posts  
- Like posts  

---

## Technologies Used

- Node.js  
- Express.js  
- JavaScript  
- Dotenv  
- REST API  
- JSON  
- Middleware  
- Postman / Thunder Client  
- Git  
- GitHub  

---

## Features

- Express server setup  
- Full CRUD operations  
- RESTful posts API  
- Middleware logging  
- Validation middleware  
- Error handling middleware  
- Environment variables support  
- Query filtering and sorting  
- Modular backend folder structure  
- API testing with Postman or Thunder Client  

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/your-github-username/iyf-s10-week-10-your-github-username.git
```

2. Navigate into the project folder

```bash
cd iyf-s10-week-10-your-github-username
```

3. Install dependencies

```bash
npm install
```

4. Start the server

```bash
npm start
```

OR

```bash
node server.js
```

5. Test the API at:

```http
http://localhost:3000/api/posts
```

---

## API Endpoints

### Get all posts

```http
GET /api/posts
```

### Get one post

```http
GET /api/posts/:id
```

### Create a post

```http
POST /api/posts
```

### Update a post

```http
PUT /api/posts/:id
```

### Delete a post

```http
DELETE /api/posts/:id
```

### Like a post

```http
PATCH /api/posts/:id/like
```

---

## Lessons Learned

Through this project I learned:

- How Node.js runs JavaScript outside the browser  
- How Express simplifies server development  
- How REST APIs work  
- How CRUD operations are built  
- How middleware processes requests  
- How to validate incoming data  
- How to handle errors properly  
- How to organize backend code into routes and controllers  
- How to use environment variables  
- How to test APIs using Postman and Thunder Client  

---

## Challenges Faced

### Challenge 1: Understanding CRUD logic

Initially it was difficult understanding how GET, POST, PUT, and DELETE work together.

Solution:

Practiced each route individually and tested each endpoint.

---

### Challenge 2: Organizing project files

Separating routes, controllers, middleware, and data was confusing.

Solution:

Used a modular project structure to keep the code organized.

---

### Challenge 3: Handling validation errors

POST requests failed when data was incomplete.

Solution:

Added validation middleware to check request data before saving posts.

---

### Challenge 4: Debugging Express errors

Some routes returned errors due to syntax and route mistakes.

Solution:

Used console logging, error middleware, and incremental testing.

## Live Demo 
[View Live Demo](https://your-deployed-)
