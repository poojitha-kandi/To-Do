<!DOCTYPE html>
<html>
<head>
  <title>To-Do List App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: white;
      color: black;
      margin: 0;
      padding: 2rem;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
    }

    h1 {
      text-align: center;
    }

    label {
      font-size: 1.2rem;
      font-weight: bold;
      display: block;
      margin-top: 2rem;
    }

    input[type="text"] {
      width: 100%;
      padding: 1rem;
      margin: 1rem 0;
      border: 1px solid gray;
      border-radius: 8px;
      font-size: 1rem;
    }

    button {
      background-color: slateblue;
      color: white;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 0.5rem;
    }

    button:hover {
      background-color: darkslateblue;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      background-color: whitesmoke;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border-radius: 5px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    li.completed {
      text-decoration: line-through;
      color: gray;
    }

    .dark-mode {
      background-color: black;
      color: white;
    }

    .dark-mode input[type="text"] {
      background-color: dimgray;
      color: white;
      border-color: gray;
    }

    .dark-mode li {
      background-color: dimgray;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Todos</h1>
    <label for="taskInput">Create Task</label>
    <input type="text" id="taskInput" placeholder="What needs to be done?" />
    <button onclick="addTask()">Add</button>

    <label>My Tasks</label>
    <ul id="todoList"></ul>
    <button onclick="toggleDarkMode()">Toggle Dark/Light Mode</button>
  </div>

  <script>
    let tasks = [];

    function addTask() {
      const taskInput = document.getElementById("taskInput");
      const taskText = taskInput.value;
      if (taskText !== "") {
        tasks.push({ text: taskText, completed: false });
        taskInput.value = "";
        displayTasks();
      }
    }

    function toggleCompleted(index) {
      tasks[index].completed = !tasks[index].completed;
      displayTasks();
    }

    function removeTask(index) {
      tasks.splice(index, 1);
      displayTasks();
    }

    function displayTasks() {
      const todoList = document.getElementById("todoList");
      todoList.innerHTML = "";
      tasks.forEach((task, index) => {
        const li = document.createElement("li");
        if (task.completed) li.classList.add("completed");
        li.innerHTML =
          '<span onclick="toggleCompleted(' + index + ')">' +
          task.text +
          '</span>' +
          '<button onclick="removeTask(' + index + ')">Delete</button>';
        todoList.appendChild(li);
      });
    }

    function toggleDarkMode() {
      document.body.classList.toggle("dark-mode");
    }
  </script>
</body>
</html>
