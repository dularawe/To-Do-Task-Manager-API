# 📝 To-Do Task Manager API

A simple and scalable RESTful API for managing to-do tasks. Built using **.NET Core** (or **Laravel**), this project includes full CRUD operations, user authentication (JWT), and task filtering.

---

## 🚀 Features

- ✅ User Registration & Login (JWT Auth)
- 📋 Create, Read, Update, Delete Tasks
- 📆 Task Deadlines & Priorities
- 📂 Category-Based Filtering
- 🔐 Secure Endpoints with Middleware
- 🌐 Clean RESTful API Structure

---

## 🧰 Tech Stack

| Layer       | Tech Used                  |
|-------------|----------------------------|
| Backend     | .NET Core Web API / Laravel |
| Auth        | JWT                        |
| Database    | SQL Server / MySQL         |
| Testing     | Postman / Swagger          |
| Deployment  | Azure / Heroku / cPanel    |

---

## 📦 API Endpoints

### Auth
- `POST /api/register` – Create new user
- `POST /api/login` – Login & receive JWT token

### Tasks
- `GET /api/tasks` – List all tasks (user-specific)
- `GET /api/tasks/{id}` – View single task
- `POST /api/tasks` – Create a new task
- `PUT /api/tasks/{id}` – Update task
- `DELETE /api/tasks/{id}` – Delete task

> All task routes are protected and require Bearer Token

---

## 🧪 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/dularawe/todo-task-manager-api.git
cd todo-task-manager-api

# For .NET
dotnet restore
dotnet run

# For Laravel
composer install
php artisan migrate
php artisan serve
