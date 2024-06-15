## Introduction
My E-Shop is a full-stack web application that allows users to browse, add to cart, and purchase clothing items. Admins have the ability to manage products and users.

## Features
User registration and authentication
Browse products by category, brand, and gender
Add products to the cart and place orders
Admin dashboard for managing products and users


## Technologies

Frontend: React, Axios, React Router
Backend: Node.js, Express, MongoDB
Authentication: JWT (JSON Web Tokens)
Styling: CSS

## Installation
Follow these steps to set up the project locally.

Prerequisites
Node.js (v14 or higher)
MongoDB

git clone https://github.com/kuriakosant/thesis-app-report.git
cd thesis-app-report

## Backend Setup
Navigate to the backend directory:
cd backend

Install the dependencies:
npm install

Create a .env file in the backend directory and add the following environment variables:
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Start the backend server:
node server.js

## Frontend Setup 

Navigate to the frontend directory:
cd ../frontend
Install the dependencies:
npm install

Create a .env file in the frontend directory and add the following environment variable:
REACT_APP_API_URL=http://localhost:5000/api

Start the frontend development server:
npm start


## Usage
Open your browser and navigate to http://localhost:3000 to view the application.
Register a new user or log in with an existing account.
Browse products, add them to your cart, and place orders.
Admin users can access the admin dashboard to manage products and users.
You can loggin as admin with the credentials : admin@gmail.com pass:123456 , these credentials can be changed from inside the database

