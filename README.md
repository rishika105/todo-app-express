
# Todo App - Backend

This is a simple Todo application built with **Node.js** and **Express.js**. The application demonstrates basic CRUD (Create, Read, Update, Delete) functionality for managing Todos.

## Features

- **Create** new Todos
- **Retrieve** existing Todos
- **Update** existing Todos
- **Delete** Todos

## Folder Structure

- **config/**: Contains configuration files (e.g., database connections).
- **controllers/**: Contains functions that handle requests and responses.
- **models/**: Contains Mongoose schema for the Todo.
- **routes/**: Defines the endpoints for the CRUD operations.
- 
## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/rishika105/todo-app-express.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo-app-express
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm start
   ```

## Tech Stack

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing Todos.
- **Mongoose**: MongoDB ORM for modeling and managing data.

## API Endpoints

- **GET** `/todos`: Fetch all todos.
- **POST** `/todos`: Create a new todo.
- **PUT** `/todos/:id`: Update an existing todo by ID.
- **DELETE** `/todos/:id`: Delete a todo by ID.
