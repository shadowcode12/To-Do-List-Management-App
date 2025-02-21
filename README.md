To-Do List Manager

 Description

 This is a simple command-line To-Do List Manager written in  Python. It allows users to:

  View their to-do list

  Add new tasks

  Mark tasks as complete

  Persist data using a JSON file

The program runs in a loop until the user chooses to exit.
## Features

1. Load and save tasks from a JSON file `(todo_list.json)`.

2. View tasks with their completion status.

3. Add new tasks to the list.

4. Mark tasks as complete.

## Prerequisites

 Python 3.x
## Installation

Clone the repository and navigate to the project directory:

```bash
  git clone https://github.com/your-username/todo-list-manager.git
cd todo-list-manager
```

## Deployment

1. Run the script using:

```bash
  python todo_list.py
```
2. Choose an option from the menu:
 1 to View Tasks

 2 to Add a Task

 3 to Mark a Task as Complete

 4 to Exit

## Code Breakdown
    file_name = "todo_list.json"

Defines the JSON file where tasks are stored.

    load_tasks()

Loads tasks from the JSON file. If the file does not exist, it returns an empty task list.

    save_tasks(tasks)

Saves the current list of tasks to the JSON file.

    view_tasks(tasks)

Displays the current list of tasks with their completion status.

    create_task(tasks)

Prompts the user to enter a task description and adds it to the task list.

    mark_tasks_complete(tasks)

Displays tasks and allows the user to mark one as complete.

    main()

Handles the main program loop, displaying the menu and processing user choices.
## Example Usage
    To-Do List Manager
    1. View Tasks
    2. Add Tasks
    3. Complete Task
    4. Exit
    Enter your choice: 2
    Enter the task description: Buy groceries
    Task added.
## Possible Improvements
Allow deleting tasks.

Enhance error handling.

Improve UI with a graphical interface.

Support task due dates and priorities.
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Fork the repository.

Create a new branch `(git checkout -b feature-branch)`.

Commit your changes `(git commit -m 'Add new feature')`.

Push to the branch `(git push origin feature-branch)`.

Open a Pull Request.


## License

This project is open-source and free to use.


## Authors

- [@shadowcode12.](https://www.github.com/shadowcode12.)
