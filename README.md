# To-Do List Management Project

This project is a web-based **To-Do List Management** application built with HTML, CSS, JavaScript for the frontend, and a **Python Flask backend** for data management. It allows users to manage tasks for different users, update task statuses, and add new tasks and users.

## Features

- **Add New User**: Create new users for task assignments.
- **Add New Task**: Assign a task to a specific user and set its status.
- **Update Task Status**: Modify the status of a task (e.g., *Yet to Start*, *In Progress*, *Completed*).
- **Filter Tasks by User**: View tasks related to a selected user.
- **View All Tasks**: Display all tasks in a table format.

## Project Structure

```
├── index.html          # Main HTML file (front end)
├── app.py              # Flask backend server script
├── data.json           # JSON file containing task data
├── users.json          # JSON file containing user data
├── requirements.txt    # Python dependencies for the Flask app
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

- Python 3 installed on your machine
- A web browser to run the application
- Basic familiarity with Python and JavaScript is helpful but not required

### Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/VenkataAmarnath/todo_flask_api.git
    cd todo_flask_api
    ```

2. **Install required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Start the Flask server**:
    ```bash
    python app.py
    ```

4. **Open `index.html` in a browser**:
    - Use "Open with Live Server" if testing locally, or access via `http://localhost:5000` if using Flask’s server.

### Usage

1. **Add a User**: Enter a name and click **Add User**.
2. **Add a Task**: Choose a user, type in the task name, select its status, and click **Add Task**.
3. **Update a Task's Status**: Select a user, pick their task, choose a new status, and click **Update Status**.
4. **View Tasks by User**: Select a user to see only their tasks.

## Notes on Static Deployment

This project currently requires a server to fetch data from `data.json` and `users.json`, so it won’t fully function on GitHub Pages or other static hosts.  
To see the project fully functioning, it's recommended to deploy it on a server environment where the data can be fetched dynamically, such as using local development servers or cloud-based services.

## GitHub Pages Link

You can view the **project preview** hosted on GitHub Pages here:  
[**Project Preview**](https://venkataamarnath.github.io/todo_flask_api/) 

Note: The preview may not function fully due to limitations on static hosting.

## Scope for Future Enhancements

- **Backend API**: Extend backend functionality to handle dynamic data updates.
- **User Authentication**: Add user login and registration.
- **Data Storage**: Integrate a database for persistent task and user data storage.

