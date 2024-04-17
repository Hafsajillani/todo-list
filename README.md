# Todo List Application

This code creates a simple todo list application using HTML, CSS, and JavaScript. Here's a breakdown of what each part does:

## HTML (index.html)

- Defines the structure of the todo list app.
- Includes a title, an input field for todo names, an input field for due dates, an "Add" button, and a container (div) for displaying the todo list.
- Links to the CSS file (style.css) for styling and the JavaScript file (script.js) for functionality.

## CSS (style.css)

- Styles the body with a font-family of Arial.
- Defines two grid layouts, one for the todo list items (todo-grid) and another for the input section (todo-input-grid).
- Styles the input fields (name-input and due-date-input) with a specific font size, padding, border, and background color.
- Styles the "Add" button (add-todo-button) with a green background, white text, and a cursor pointer.
- Styles the "Delete" button (delete-todo-button) with a dark red background, white text, no border, a specific font size, and a cursor pointer.

## JavaScript (script.js)

- Defines an array todoList that contains objects representing todo items, each with a name and dueDate.
- Defines a function renderTodoList that generates HTML for each todo item and displays it in the .js-todo-list element.
- Attaches an event listener to each "Delete" button to remove the corresponding todo item from the todoList array and re-render the todo list.
- Defines a function addTodo that adds a new todo item to the todoList array using the values from the input fields and then re-renders the todo list.
- Attaches an event listener to the "Add" button to call the addTodo function when clicked.

Overall, this code creates a basic todo list application where users can add new todo items, see a list of existing todo items with their due dates, and delete items from the list.

![todo-list](https://github.com/Hafsajillani/todo-list/assets/103882246/0e1e71ae-4086-4e96-b304-19f42ca0df9c)
