<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sprint Summarizer</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    .summary { margin-bottom: 20px; }
    .task { background-color: #f9f9f9; padding: 10px; margin-bottom: 10px; border-radius: 5px; }
    .completed { background-color: #d3f9d8; }
  </style>
</head>
<body>

  <h1>Sprint Summarizer</h1>
  
  <div class="summary">
    <h2>Summary of Sprint: <span id="sprint-title"></span></h2>
    <p id="sprint-description"></p>
  </div>

  <div class="tasks">
    <h3>Tasks Completed:</h3>
    <div id="completed-tasks"></div>

    <h3>Remaining Tasks:</h3>
    <div id="remaining-tasks"></div>
  </div>

  <script>
    // Fetch sprint summary data from the backend (server)
    fetch('/sprint-summary')
      .then(response => response.json())
      .then(data => {
        // Populate the sprint data on the page
        document.getElementById('sprint-title').textContent = data.title;
        document.getElementById('sprint-description').textContent = data.description;

        const completedTasksDiv = document.getElementById('completed-tasks');
        const remainingTasksDiv = document.getElementById('remaining-tasks');

        // Show completed tasks
        data.completedTasks.forEach(task => {
          const taskDiv = document.createElement('div');
          taskDiv.classList.add('task', 'completed');
          taskDiv.textContent = task.name;
          completedTasksDiv.appendChild(taskDiv);
        });

        // Show remaining tasks
        data.remainingTasks.forEach(task => {
          const taskDiv = document.createElement('div');
          taskDiv.classList.add('task');
          taskDiv.textContent = task.name;
          remainingTasksDiv.appendChild(taskDiv);
        });
      });
  </script>
</body>
</html>
