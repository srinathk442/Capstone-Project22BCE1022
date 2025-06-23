# Blogging Platform — MERN Stack

A full-featured blogging web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). The platform enables users to register, log in, create and manage blog posts, and securely upload images. CAPTCHA verification is integrated to protect against automated submissions, and full CRUD functionality is provided for managing blog content.

---

## 🔧 Features

- User authentication with JWT
- CAPTCHA verification for bot protection
- Image/file upload support (via Multer and Cloudinary/local)
- Create, edit, delete, and view blog posts
- RESTful API built with Express.js
- Responsive frontend built with React
- MongoDB database for storing users and posts

---

## 🧠 Modules

- **Authentication** – Signup, login, and protected routes using JWT
- **CAPTCHA** – Human verification during login/registration
- **Blog Post CRUD** – Full create, update, delete, and read functionality
- **File Uploads** – Integrated image upload via Multer
- **Frontend Interface** – Built with React and Axios

---

## 🛠️ Getting Started

1. Clone the repository:
   `git clone https://github.com/your-username/blog-app.git`

2. Set up environment variables in both `frontend/.env` and `backend/.env`:
   - MongoDB URI
   - JWT Secret
   - Cloudinary credentials (if used)

3. Install dependencies and run:
   - `npm install` in both `frontend/` and `backend/`
   - `npm start` to launch both servers

4. Visit `http://localhost:3000` to use the app.

---


## Instructions

cd into the client and server folders and do 
npm i to install the modules before running

For running locally:
Edit the .env file in the client and change the REACT_APP_SERVER_URL = http://localhost:4000

To run the server edit the environment variables and change the secret key and mongodb url if you want to run from your database

For vercel configuration change the environment variables accordingly
 Enter your mongodb and secret key in the .env file of the server
