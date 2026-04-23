# Task Manager App

A simple Task Manager API built with Node.js and Express.
This project demonstrates basic CRUD operations and project structure for a backend application.

## 🚀 Features

* Create a task
* Get all tasks
* Update a task
* Delete a task
* Store data in a local JSON file

## 🛠️ Tech Stack

* Node.js
* Express

## 📦 Installation

```bash
git clone https://github.com/your-username/task-manager-app.git
cd task-manager-app
npm install
```

## ▶️ Run the App

```bash
npm start
```

Server will run on:

```
http://localhost:3000
```

## 📌 API Endpoints

| Method | Endpoint   | Description   |
| ------ | ---------- | ------------- |
| GET    | /tasks     | Get all tasks |
| POST   | /tasks     | Create a task |
| PUT    | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## 📁 Project Structure

* `routes/` - API routes
* `controllers/` - Business logic
* `models/` - Data handling
* `data/` - JSON storage

## 📄 License

This project is licensed under the MIT License.
