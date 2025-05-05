# 📝 React ToDo List App

![React ToDo List Banner](banners/banner.png)

A simple and elegant ToDo List web application built with **React.js**. It allows users to **create**, **read**, **update**, and **delete** tasks with a sleek component-based UI.

## ⚛️ Features

- ✅ Add new tasks
- 📋 View a list of all your tasks
- ✏️ Edit existing tasks
- ❌ Delete completed or unwanted tasks
- 💡 Interactive UI with reusable components

## 🧩 Components

### 1. `TodoInput`
Handles user input for adding and editing tasks. Contains:
- A text input field
- Add / Save button
- Input validation

### 2. `TodoCard`
Represents a single task item. Contains:
- Task text
- Edit button
- Delete button

### 3. `TodoList`
Displays a list of all tasks using the `TodoCard` component.

## 🚀 Getting Started

### Prerequisites

Make sure you have Node.js and npm installed.

```bash
node -v
npm -v
```

### Installation

1. Clone the repo:
```bash
git clone https://github.com/shreeramkedlaya/reactjs-todolist.git
cd todo-react-app
```

2. Install dependencies:
```bash
npm install
```

3. Run the app:
```bash
npm start
```

App will run locally at `http://localhost:3000`

## 📁 Project Structure

```
todo-react-app/
│
├── src/
│   ├── assets/
│   │   ├── react.svg
│   ├── components/
│   │   ├── TodoInput.jsx
│   │   ├── TodoCard.jsx
│   │   └── TodoList.jsx
│   ├── App.jsx
│   └── index.js
│
├── public/
│   └── index.html
│
├── package.json
└── README.md
```

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6+)
- CSS Modules / Plain CSS

## 📦 Future Improvements

- Add task completion toggle with strikethrough
- Add categories or tags
- Persist tasks using localStorage or a backend

## 🧑‍💻 Author

Made with ❤️ by **Shreeram Kedlaya**

Happy Coding! 🚀
