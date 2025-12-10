# 📋 Task Tracker App

Task Tracker App is a simple and clean iOS application built using **Swift** and **UIKit**.  
It allows users to:

- Add new tasks
- View all tasks in a list
- Filter **Completed** and **Pending** tasks using a UIBarButtonItem
- Manage tasks with a lightweight in-memory model

---

## 🚀 Features

### ✔ Task Model

Each task contains:

- `title` – Name of the task
- `description` – Details about the task
- `status` – Boolean indicating if the task is completed

### ✔ Task List UI

- Displays all tasks in a `UITableView`
- Dynamically reloads data when tasks are added or filtered

### ✔ Filter Button

A `UIBarButtonItem` in the main `ViewController` allows filtering:

- **Show All**
- **Show Completed Only**
- **Show Pending Only**
