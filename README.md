# Simple-Task-Java

## 1. Introduction
The Simple Task List Application provides a minimalistic interface for users to manage their daily tasks. Users can create new tasks, view existing tasks, and delete completed or unnecessary tasks. This application is ideal for users who prefer a straightforward solution for keeping track of tasks without the complexity of a full-fledged project management tool.

## 2. Features
Create New Tasks: Users can add new tasks with a description.
List All Tasks: Display all current tasks with their corresponding indices.
Delete Tasks: Remove tasks by specifying the index.
Exit the Application: Safely terminate the application.
## 3. File Overview
Main.java: This file contains the main entry point of the application. It handles user interactions and invokes methods to perform operations like adding, listing, and deleting tasks.
Taskmenu.java: This file contains the logic and operations related to task management. It manages the task list and provides methods for task operations such as adding, listing, and deleting.
## 4. Class Structure
Main Class:
Contains the main method, which is the entry point of the application.
Interacts with the user and calls methods from the Taskmenu class to perform operations.
Taskmenu Class:
Manages the list of tasks.
Provides methods to add, list, and delete tasks.
Uses an ArrayList to store task descriptions, providing dynamic task management.
## 5. Usage
Running the Application: Execute the Main.java file to start the application.
Adding a Task: Follow the on-screen instructions to add a new task by entering a description.
Listing Tasks: Select the option to list all current tasks.
Deleting a Task: Choose the delete option and specify the index of the task to be removed.
Exiting: Choose the option to exit the application safely.
## 6. Future Enhancements
Implement a feature to edit existing tasks.
Add a functionality to mark tasks as completed.
Implement a file-based storage system to persist tasks between sessions.
