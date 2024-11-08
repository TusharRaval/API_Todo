#To-DO API

A basic Express.js API for managing a to-do list, allowing users to create, retrieve, update, and delete tasks. This project demonstrates simple RESTful API operations with in-memory data storage.

##Features

-> Create Task: Add a new task to the to-do list.
-> Get All Tasks: Retrieve all tasks in the to-do list.
-> Get Task by ID: Retrieve a specific task by its ID.
-> Update Task: Modify an existing task by its ID.
-> Delete Task: Remove a task from the list by its ID.

##Prerequisites

-> Node.js and npm installed on your local machine.

##Clone the repository
  git clone https://github.com/your-username/to-do-api.git
cd to-do-api

##Install dependencies
  npm install

##Run the server
  node index.js

The server will start on http://localhost:3000.

#API Endpoints
  ##Fetch All Tasks
    Endpoint: /tasks
    Method: GET
    Description: Retrieve all tasks.

  ##Fetch a Task by ID
    Endpoint: /tasks/:id
    Method: GET
    Description: Retrieve a task by its unique ID.

  ##Create a New Task
    Endpoint: /tasks
    Method: POST
    Description: Adds a new task to the list.

  ##Update a Task by ID
    Endpoint: /tasks/:id
    Method: PUT
    Description: Updates the task details.

  ##Delete a Task by ID
    Endpoint: /tasks/:id
    Method: DELETE
    Description: Deletes the specified task.
    Response: 204 No Content (if successful)

  ##Error Responses
    404 Not Found: Returned if the specified task ID is not found.


#Running Tests
For simplicity, this project currently doesn't include automated tests, but you can manually test it using a tool like Postman

    
