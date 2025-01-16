# Task_Manager
PLP Academy Flask Practise


# Task Manager App in Flask

## Overview
The Task Manager App is a simple web application developed using the Flask framework. It allows users to manage tasks and projects efficiently. The app provides functionalities to add, close, delete, and clear tasks, as well as switch between different project tabs.

## Importance
1. **Task Organization**: Helps users organize tasks under different projects, making it easier to manage and prioritize work.
2. **User-Friendly Interface**: Provides a clean and intuitive interface for task management.
3. **Flexibility**: Allows users to switch between different project tabs, making it versatile for various use cases.
4. **Persistence**: Uses SQLite database to store tasks and projects, ensuring data persistence across sessions.

## Key Features
- **Add Tasks**: Users can add new tasks to a specific project. If the project does not exist, it will be created automatically.
- **Close/Reopen Tasks**: Users can mark tasks as completed or reopen them if needed.
- **Delete Tasks**: Tasks can be deleted individually.
- **Clear Tasks**: Users can clear all tasks from a specific project or delete the entire project.
- **Switch Projects**: Users can switch between different project tabs to focus on specific tasks.

## How to Use
1. **Home Page**: The home page displays all tasks and projects. The active project tab is highlighted.
2. **Adding a Task**:
   - Enter the task description in the input field.
   - Optionally, specify the project name. If not provided, the task will be added to the default "Tasks" project.
   - Click "Add" to add the task.
3. **Closing/Reopening a Task**:
   - Click the checkbox next to a task to mark it as completed or reopen it.
4. **Deleting a Task**:
   - Click the delete icon next to a task to remove it.
5. **Clearing Tasks**:
   - To clear all tasks from a project, click the "Clear" button next to the project name.
   - To delete the entire project, click the "Delete" button next to the project name.
6. **Switching Projects**:
   - Click on a project tab to switch to that project and view its tasks.

## Setup and Running the App
1. **Install Dependencies**: Ensure you have Python and Flask installed. Install the required packages using `pip install flask flask-sqlalchemy`.
2. **Run the App**: Execute the script using `python app.py`.
3. **Access the App**: Open a web browser and navigate to `http://127.0.0.1:5000/` to use the app.

## Conclusion
The Task Manager App is a practical tool for individuals and teams to manage their tasks and projects effectively. Its simplicity and ease of use make it an excellent choice for anyone looking to improve their productivity and task management skills.
