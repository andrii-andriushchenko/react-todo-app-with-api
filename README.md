# React Todo App with API

This is a simple Todo list application built using React and an API for data management. The application allows users to add, remove, and edit Todo items, as well as mark them as completed or incomplete.

Getting Started To get started with the application, you can simply visit the deployed version of the app at the link: [DEMO](https://andrii-andriushchenko.github.io/react_todo-app-with-api/)

Usage To use the Todo application, simply enter a task into the input field at the top of the page and press "Enter" or click the "Add" button. To mark a task as completed, click the checkbox next to the task. To edit or delete a task, click the corresponding icons on the right side of the task.

The application uses an API to manage the Todo data. The API is built using Node.js and Express.

The API has the following endpoints:

GET /todos: returns a list of all Todo items

POST /todos: adds a new Todo item

PUT /todos/:id updates an existing Todo item with the given ID

DELETE /todos/:id deletes an existing Todo item with the given ID
