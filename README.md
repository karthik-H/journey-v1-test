# journey-v1-test
dev v1 test
# curly-barnacle-task-tracker
# TaskTracker


A simple Task Tracker application to manage tasks and users with a lightweight in-memory storage approach.

## Features

### 1. CRUD for Tasks
- Create, Read, Update, Delete tasks.
- Each task should have:
  - **Unique ID**
  - **Title**
  - **Description**
  - **Status**: `To Do`, `In Progress`, `Done`
  - **Due Date**
  - **Priority**

### 2. User Management
- Add, edit, delete users.
- Each user should have:
  - **Unique ID** 
  - **Name**
  - **Email**
  - **Role**

### 3. Assign & Reassign Tasks
- Assign one or more users to a task.
- Reassigning updates the task’s assignees without deleting the task.

### 4. View Tasks
- View tasks using filters:
  - By **User**
  - By **Status**
  - By **Due Date**
  - By **Priority**

### 6. Storage
- No external storage (e.g., database, files).
- All data stored in **variables (in-memory)**.

---

## Deliverables

- **Python source code** organized into modules:
  - `models/`
  - `services/`
  - `routes/`
- **UI** to interact with the application.
- **requirements.txt** file for dependencies.
- **README.md** file with setup and usage instructions.

---