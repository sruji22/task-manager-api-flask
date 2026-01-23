# Task Manager API (Flask)

A simple Flask REST API to manage tasks (CRUD operations) using SQLite.

## Features
- Create a new task
- View all tasks
- Update task status
- Delete tasks
- SQLite database for storage

## Tech Stack
- Python
- Flask
- SQLite
## How to Run
## API Endpoints

| Method | Endpoint         | Description        |
|--------|------------------|-------------------|
| POST   | /tasks           | Create a new task |
| GET    | /tasks           | Get all tasks     |
| PUT    | /tasks/<id>      | Update a task     |
| DELETE | /tasks/<id>      | Delete a task     |


```bash
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt
python3 app.py





