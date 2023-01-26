# FastBooks API

My first RESTful API!

This is a RESTful API built using Node.js, Express, MongoDB, Mongoose, JWT, and other Node.js libraries. The API allows for CRUD operations on a MongoDB database, authentication and authorization using bcrypt and JWT, error handling with express and much more. 

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
Node.js
MongoDB
npm

# Installing
-Clone the repository to your local machine by running 'git clone https://github.com/henriquebuzon/FastBooks'

-Install the dependencies running 'npm install'

-Create a .env file in the root of the project and set the following variables:
MONGO_URI=mongodb://<username>:<password>@<host>:<port>/<database>
JWT_SECRET=<yoursecret>
  
-Start the development server by running 'npm start' 
The API will be running on http://localhost:3000

# Author
Henrique Buzon - https://github.com/henriquebuzon
