# Express + MongoDB + Pug CRUD App

This is a simple full-stack web application built with **Express.js**, **MongoDB**, and **Pug** as the template engine. It supports CRUD operations (Create, Read, Update, Delete) for managing both **students** and **employees**, organized in separate folders.

## 📁 Project Structure

```
Express+Mongo+Pug/
│
├── students/
│   ├── models/
│   │   └── student.js
│   ├── views/
│   │   ├── layout.pug
│   │   ├── index.pug
│   │   ├── new.pug
│   │   └── edit.pug
│   ├── public/
│   │   └── style.css
│   └── server.js
│
├── employees/
│   ├── models/
│   │   └── employee.js
│   ├── views/
│   │   ├── layout.pug
│   │   ├── index.pug
│   │   ├── new.pug
│   │   └── edit.pug
│   ├── public/
│   │   └── style.css
│   └── server.js
│
└── README.md
```

---

## 📦 Features

- Pug templating engine for clean and dynamic HTML rendering
- MongoDB for data storage
- Express for routing and server logic
- Two separate modules: **Students** and **Employees**
- Clean UI with form validation

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally on `mongodb://127.0.0.1:27017`

### Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd Express+Mongo+Pug

# For students module
cd students
npm install

# For employees module
cd ../employees
npm install
```

---

## 🛠️ Running the Servers

Open two terminals:

### Terminal 1: Students Module

```bash
cd students
node server.js
# App running at http://localhost:3000
```

### Terminal 2: Employees Module

```bash
cd employees
node server.js
# App running at http://localhost:3001 (adjust port if needed)
```

---

## 🧪 Routes

### Students

- `/` - List all students
- `/new` - Add new student
- `/edit/:id` - Edit student
- `/delete/:id` - Delete student

### Employees

- `/` - List all employees
- `/new` - Add new employee
- `/edit/:id` - Edit employee
- `/delete/:id` - Delete employee

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).