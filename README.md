Project Name
This project is a simple backend application built with Node.js and MongoDB. It provides a RESTful API for managing tasks. The server is set up using Express.js, and MongoDB is used as the database to store task data.

Getting Started
To get started with this project, clone the repository and install the necessary dependencies using npm install. Make sure MongoDB is installed and running on your local machine. Update the MongoDB connection URI in server.js if necessary, and then start the server with npm start. The server will run on http://localhost:5000.

Usage
Once the server is running, you can use tools like Postman to interact with the API endpoints. Available endpoints include:

GET /tasks: Retrieve all tasks.
POST /tasks: Create a new task.
GET /tasks/:id: Retrieve a task by ID.
PUT /tasks/:id: Update a task by ID.
DELETE /tasks/:id: Delete a task by ID.
MongoDB Setup
Ensure MongoDB is installed and running locally. Update the MongoDB connection URI in server.js to point to your local MongoDB instance.