# 📌 To-Do List Application

A simple To-Do List application using **Laravel 12** (Backend) and **Next.js** (Frontend).

## 🛠 Features
✅ Create, Read, Update, Delete (CRUD) tasks  
✅ Mark tasks as completed  
✅ Responsive UI using TailwindCSS  
✅ API documentation using OpenAPI/Swagger  

---

## 📂 Project Structure
📦 todo-app 
    ┣ 📂 todo-backend (Laravel 12) 
    ┣ 📂 todo-frontend (Next.js + React Query) 
    ┣ 📜 README.md


---

## 🚀 Getting Started

### 🔹 1. Running todo-backend (Laravel 12)
#### 1️⃣ Clone Repository and Navigate to Backend
```sh
git clone <repository-url>
cd backend
```
#### 2️⃣ Install Dependencies
composer install

#### 3️⃣ Setup Environment
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=todo_db
DB_USERNAME=root
DB_PASSWORD=

#### 4️⃣ Generate Application Key

php artisan key:generate

#### 5️⃣ Run Migrations & Seeders
php artisan migrate --seed

#### 6️⃣ Start the Backend Server
php artisan serve

===
🔹 2. Running todo-frontend (Next.js)

#### 1️⃣ Navigate to Frontend
cd frontend

#### 2️⃣ Install Dependencies
npm install

#### 3️⃣ Start the Frontend Server
npm run dev

===
## 📜 API Documentation (Swagger / OpenAPI)
### 📝 API Endpoints
| Method | Endpoint         | Description                        |
|--------|-----------------|------------------------------------|
| GET    | `/api/tasks`     | Get all tasks                     |
| POST   | `/api/tasks`     | Create a new task                 |
| PUT    | `/api/tasks/{id}` | Update a task (mark as completed) |
| DELETE | `/api/tasks/{id}` | Delete a task                     |
