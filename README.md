# 📝 Todo App (HTML, CSS, JavaScript)

A simple and responsive **Todo List Web App** built using **HTML, CSS, and Vanilla JavaScript**.
Tasks are stored in the browser using **Local Storage**, so your list remains saved even after refreshing the page.

---

## 🚀 Features

* Add new tasks
* Mark tasks as completed (click on task)
* Delete tasks
* Data saved in browser using Local Storage
* Clean and responsive UI
* No frameworks required

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Browser LocalStorage API

---

## 📂 Project Structure

```
todo-app/
│
├── index.html   # Main application file (HTML + CSS + JS)
└── README.md    # Project documentation
```

---

## ▶️ How to Run the Project

1. Download or clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app.git
   ```

2. Open the project folder.

3. Double-click `index.html`
   **or** open it in any browser.

No installation or setup required.

---

## 💡 How It Works

* Tasks are stored in an array called `tasks`.
* When a task is added, deleted, or toggled:

  * The array updates
  * Data is saved to `localStorage`
  * UI re-renders automatically

### Local Storage Format

```json
[
  { "text": "Study JavaScript", "completed": false },
  { "text": "Build project", "completed": true }
]
```

---

## 🖥️ UI Preview

* Input field to enter task
* Add button
* Click task → mark complete
* Delete button → remove task

---

## 📈 Future Improvements

You can enhance this project by adding:

* Edit task feature
* Dark mode
* Task deadline/date
* Filter (All / Completed / Pending)
* Drag and drop sorting
* Backend (Node.js + Database)
* Login system

---

## 🎓 Good For

* Beginners learning JavaScript
* DOM manipulation practice
* LocalStorage practice
* College mini project
* Portfolio project

---

## 👨‍💻 Author

**Your Name**
B.E CSE Student
GitHub: https://github.com/your-username

---

## ⭐ Contribute

Pull requests are welcome.
For major changes, open an issue first to discuss what you'd like to change.

---

## 📜 License

This project is open-source and free to use for learning purposes.

