# TodoList-Project-VanillaJS
![TodoList image](https://github.com/pranayainchwar/TodoList-Project-VanillaJS/assets/122523118/8c114b1d-8e7f-4fdb-b9f2-e6f28cd2905e)
Visite App: https://pranayainchwar.github.io/TodoList-Project-VanillaJS/
Welcome to our Todo List project where we'll dive into the JavaScript functionality driving this application. Our goal is to understand how tasks are added, marked as completed, and how the dark mode feature toggles the theme. Let's break down the script step by step.
Variable Declarations:
"We start by declaring variables to interact with various elements in our HTML. These include root, container, newTaskInput, taskform, tasksList, taskBtns, and themeBtn. These variables allow us to access different parts of our webpage."

Form Submission Event Listener:
"Our script listens for the form submission event (taskform.addEventListener). When a user submits a task, we prevent the default form behavior (e.preventDefault()) to avoid page reloads. Then, we extract the value of the input field (newtaskInputValue) and pass it to the addTask function."

addTask Function:
"The addTask function creates a new task item by dynamically generating HTML elements (<li>, <div>, <span>) and appending them to our tasks list (tasksList). This function helps us visually represent the added tasks on the webpage."

onTaskComplete Function:
"The onTaskComplete function handles the completion of tasks. It listens for clicks on the task completion button (btns.addEventListener). Once clicked, it identifies the parent task item and marks it as completed with a transition before removing it from the list."

Dark Mode Functionality:
"Our dark mode feature is triggered by clicking the theme button (themeBtn.addEventListener). This function toggles the dark class on the theme button, allowing us to switch between light and dark modes by adjusting CSS variables (root.style.setProperty) for colors, transitions, and images."

Conclusion:
"By combining HTML, CSS, and JavaScript, we've created a functional Todo List application. JavaScript handles user interactions, adding tasks, marking them as completed, and implementing a dark mode feature. This breakdown helps us understand the backbone of our Todo List's functionality."
