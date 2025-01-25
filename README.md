# Simple Blog With CRUD operation, Login & Register Feature - MERN STACK
Here is the deployed project https://salekin-simple-blog-frontend.onrender.com

![MERN Stack](https://img.shields.io/badge/MERN-Full%20Stack-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

A full-stack blog application built with the MERN stack (MongoDB, Express.js, React, and Node.js) that allows users to create, read, update, and delete blog posts. Includes user authentication, rich text editing, and image uploads.

## Features

- **User Authentication**: Secure JWT-based registration and login system.
- **CRUD Operations**: Create, read, update, and delete blog posts.
- **Rich Text Editor**: Integrated with React Quill for enhanced content creation.
- **Image Uploads**: Supports image uploads for blog posts using Multer.
- **Responsive UI**: Clean and modern design with React.js and Tailwind CSS.
- **Search Functionality**: Filter blog posts by keywords or categories.
- **RESTful API**: Backend built with Express.js and Node.js for scalability.

## Live Demo

Explore the live demo [here](https://salekin-simple-blog-frontend.onrender.com) (replace with your deployed link).

## Technologies Used

- **Frontend**: React.js, Tailwind CSS, Axios, React Quill, React Router
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT, Bcrypt, Multer
- **Tools**: Postman, Git, GitHub

## Installation

Follow these steps to run the project locally:

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account or local MongoDB instance
- Git

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/rupaksalekin2018/simple-blog-app-MERN.git
   cd simple-blog-app-MERN

### install dependencies
# Install server dependencies
cd server
npm install

# Install client dependencies for node server
cd server
npm install

# Install client dependencies for client server
cd ../client
npm install

# Create a .env file in the server directory Add these:
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    PORT=5000

 # Create a .env file in the client directory:
    REACT_APP_API_URL=http://localhost:5000

Start the Application
# Run the server (from /server directory)
npm start

# Run the client (from /client directory)
npm start   

API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Authenticate a user
GET	/api/posts	Fetch all blog posts
POST	/api/posts	Create a new blog post
PUT	/api/posts/:id 	Update a blog post
DELETE	/api/posts/:id 	Delete a blog post
