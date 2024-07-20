# Express-Todo-App
This project is an Express.js application that connects to MongoDB, handles todo list operations via RESTful routes, and uses EJS for templating.

## Structure
   - app.js: Entry point of the application where Express is configured and routes are defined.
   - index.js: Initializes the Express application and starts the server on the specified port.
   - init/mongodb.js: Contains logic to connect to MongoDB using Mongoose or native MongoDB driver.
   - routes/todo.js: Example route file where todo-related routes are defined.
   - public/: Directory for static assets like CSS, images, etc.
   - views/: Directory for view templates (if using a view engine like EJS).

## Dependencies
   - Express: Web framework for Node.js
   - Body-parser: Middleware to handle HTTP POST request bodies
   - dotenv: Loads environment variables from a .env file into process.env
   - Mongoose (optional): MongoDB object modeling tool (if using Mongoose for MongoDB interactions)

## Usage
1. Starting the Server: The server is started by running `index.js`.
2. Accessing Routes:
   - Todo Routes: Defined in routes/todo.js, accessible from http://localhost:8000/.
