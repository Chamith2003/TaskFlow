# ✅ TaskFlow

A clean, minimal todo list application built with **React** and **Vite**. TaskFlow helps you organize your daily tasks with an intuitive interface — add, complete, and delete tasks effortlessly.

---

## ✨ Features

- **Add Tasks** — Quickly add new todo items via the input form
- **Mark as Complete** — Click on a task to toggle its completion status
- **Delete Tasks** — Remove tasks you no longer need
- **Auto-Sort** — Completed tasks automatically move to the bottom of the list
- **Live Progress** — Footer displays completed vs. total task count in real-time

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React 19](https://react.dev/) | UI library |
| [Vite 8](https://vite.dev/) | Build tool & dev server |
| [CSS Modules](https://github.com/css-modules/css-modules) | Scoped, component-level styling |
| [ESLint](https://eslint.org/) | Code linting |

---

## 📁 Project Structure

```
taskflow/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.jsx          # App title header
│   │   ├── Form.jsx            # Input form to add new todos
│   │   ├── Todo.jsx            # Main container managing todo state
│   │   ├── TodoList.jsx        # Renders sorted list of todo items
│   │   ├── TodoItem.jsx        # Individual todo item (toggle & delete)
│   │   ├── Footer.jsx          # Completed/total task counter
│   │   ├── header.module.css
│   │   ├── form.module.css
│   │   ├── todoitem.module.css
│   │   ├── todolist.module.css
│   │   └── footer.module.css
│   ├── App.jsx                 # Root component
│   ├── App.css                 # Global app styles
│   └── main.jsx                # Entry point
├── index.html
├── package.json
├── vite.config.js
└── eslint.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Chamith2003/TaskFlow.git
   cd TaskFlow
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:5173`)

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the Vite development server with HMR |
| `npm run build` | Build the app for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint to check for code issues |

---

## 🧩 Component Overview

```
App
├── Header          → Displays the app title
└── Todo            → Manages todo state (useState)
    ├── Form        → Handles user input and adding new todos
    ├── TodoList    → Sorts and renders all todo items
    │   └── TodoItem  → Displays a single todo with toggle & delete
    └── Footer      → Shows completed / total count
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
