# To-Do List Project

This is a simple To-Do List project built with HTML, CSS, and JavaScript. It allows users to add, delete, and mark tasks as complete. The project also includes filtering options to view completed, incomplete, or all tasks.

## Table of Contents

- [Features](#features)
- [File Structure](#file-structure)
- [Functionality](#functionality)
- [How to Use](#how-to-use)

## Features

- Add new tasks
- Delete existing tasks
- Mark tasks as complete/incomplete
- Filter tasks by status (all, complete, incomplete)
- Delete all tasks
- Local storage to persist tasks
- Responsive Design
- Visually Appealing UI

## File Structure

```
├── index.html // Front page of the website
├── index1.html // Main page of the To-Do List
├── script.js  // JavaScript file for To-Do List functionality
├── front.css // CSS file for styling the front page
└── styles.css  // CSS file for styling the To-Do List
└── README.md // Documentation

```

## Functionality

### `script.js`

This file contains the JavaScript code that powers the To-Do List functionality.

- **`showTodos()`:** Renders the To-Do List items in the `todosHtml` element based on the current filter. If no tasks exist, it displays an empty image.
- **`addTodo(todo)`:** Adds a new task to the `todosJson` array, updates local storage, and refreshes the displayed list.
- **`updateStatus(todo)`:** Updates the status of a task to complete or pending and updates local storage.
- **`remove(todo)`:** Removes a task from the `todosJson` array, updates local storage, and refreshes the displayed list.
- **Event Listeners:**
    - The script listens for "keyup" events on the input field to add tasks when the Enter key is pressed.
    - It listens for "click" events on the add button to add new tasks.
    - It listens for "click" events on the filter elements to filter the displayed tasks.
    - It listens for a "click" event on the "Delete All" button to remove all tasks.

### `index.html`

This file contains the HTML structure of the To-Do List.

- **Input Field:** Allows users to enter new tasks.
- **Add Button:** Adds the entered task to the list.
- **Filters:** Contains buttons to filter tasks by "Complete", "Incomplete", and "Delete All".
- **To-Do List:** Displays the list of tasks.
- **Empty Image:** Shown when the To-Do List is empty.

### `index1.html`

This file contains the basic HTML structure with links to CSS and JavaScript files. It sets up the page with a title and includes the necessary elements for the To-Do List.

### `styles.css`

This CSS file styles the appearance of the To-Do List. It defines the layout, colors, fonts, and styling for various elements.

### `front.css`
This CSS file defines the visual presentation of the web page, such as layout, typography, colors, and responsiveness, enhancing its aesthetic appeal and user experience.

## How to Use

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Start adding tasks using the input field and add button.
4. Mark tasks as complete by clicking the checkbox next to them.
5. Delete individual tasks using the delete button next to each task.
6. Use the filter buttons to view tasks by their status.
7. Click "Delete All" to clear the entire To-Do List.

The To-Do List will automatically save your tasks in local storage, so they will be available the next time you open the application.
