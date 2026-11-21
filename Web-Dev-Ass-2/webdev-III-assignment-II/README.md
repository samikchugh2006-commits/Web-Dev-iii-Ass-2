# 🎓 Student Management REST API

Simple REST API built using **Node.js** and **Express.js** to manage student records using CRUD operations.

## 🔧 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/manpreetkaur292006-design/Student-Management-REST-API.git
```

### 2️⃣ Open the project folder

```bash
cd Student-Management-REST-API
```

### 3️⃣ Install dependencies

```bash
npm install
```

## ▶️ Run the Server

Start the development server using:

```bash
npm run dev
```

The server will run at:

```text
http://localhost:3000
```

## 📡 API Endpoints

| Method     | Endpoint        | Description         |
| ---------- | --------------- | ------------------- |
| 🟢 GET     | `/students`     | Get all students    |
| 🔎 GET     | `/students/:id` | Get a student by ID |
| ➕ POST     | `/students`     | Add a new student   |
| ✏️ PUT     | `/students/:id` | Update a student    |
| 🗑️ DELETE | `/students/:id` | Delete a student    |