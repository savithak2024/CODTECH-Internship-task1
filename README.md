Name : Savitha k
Company : CODTECH IT SOLUTIONS INTERNSHIP
Id : CT04DS7522
Domain : Web Development
Duration : 25th August, to 25th September, 2024

Overview of the project
Project : To Do List (web app)

Objective:
This JavaScript code is part of a To-Do List application that allows users to:
Add tasks to a list.
Mark tasks as complete by clicking on them.
Delete tasks by clicking on a delete icon (×).
Store the list in the browser's local storage so that the tasks persist even after refreshing or closing the page.

Key Activities:
Add Task:
The addTask() function is triggered when a user types a task into the input box and submits it (typically by pressing a button).
The function checks if the input field is empty. If it is, an alert tells the user that they must write something
Task Interactions (Mark Complete or Delete):
An event listener is attached to the listcontainer (the ul element).
If a user clicks on a task (the li), the checked class is toggled, which visually marks the task as complete (usually by applying a strikethrough).

Technology Used:
HTML:
Provides the structure of the application, including input fields, buttons, and list elements to display tasks.
CSS:
Used for styling the application, including the layout, fonts, colors, and hover effects.
JavaScript:
Provides the interactivity and logic for the application.
Document Object Model (DOM) manipulation is used to dynamically add, modify, and remove elements (tasks) in the list.
Event Handling: Events like clicking on tasks or the delete button are captured and processed to update the task list accordingly.
Local Storage: The browser's local storage is used to save the task list so that it persists between sessions (page reloads, browser restarts). This is done using localStorage.setItem() to store data and localStorage.getItem() to retrieve data.
