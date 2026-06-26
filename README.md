# Task Management App

A simple and clean command-line Task Management application built with Python.

This app allows you to:
- Add tasks
- Update existing tasks
- Delete tasks
- View all current tasks

It is designed as a beginner-friendly CLI project with improved structure and input handling.

## Features

- Interactive menu-driven interface
- Initial task setup at startup
- Safe number input handling
- Validation for empty task names
- Graceful handling for missing tasks on update/delete
- Clean function-based code organization

## Project Structure

```text
Task-Management-App/
|- app.py
|- README.md
```

## Requirements

- Python 3.8+

## Setup

1. Clone or download this project.
2. Open the project folder in VS Code or terminal.
3. (Optional) Create and activate a virtual environment.

### Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Install dependencies

No external dependencies are required.

## Run the App

```bash
python app.py
```

If you are using this workspace virtual environment, you can run:

```bash
.venv/Scripts/python.exe app.py
```

## How to Use

1. Enter how many tasks you want to add initially.
2. Provide each task name.
3. Use the menu options:
   - 1: Add a new task
   - 2: Update an existing task
   - 3: Delete a task
   - 4: View all tasks
   - 5: Exit the app

## Example Workflow

```text
----WELCOME TO THE TASK MANAGEMENT APP----
Enter how many tasks you want to add = 2
Enter task 1 = Buy milk
Enter task 2 = Finish report

1-Add
2-Update
3-Delete
4-View
5-Exit/Stop
```

## Code Quality Notes

The current implementation is organized into focused functions for:
- input parsing
- task initialization
- add/update/delete/view operations
- menu loop control

This makes the code easier to read, test, and extend.

## Future Improvements

- Persistent storage (save tasks to JSON or SQLite)
- Due dates and priorities
- Task status tracking (Pending/Done)
- Search and filter support
- Unit tests with pytest

## License

This project is open for learning and personal use.
