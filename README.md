# 📋 Command Line Task Manager

A simple Python command-line application that allows users to manage daily tasks.

The program stores tasks in a JSON file and allows adding, viewing, and updating task status directly from the terminal.

---

## 👥 Authors

* Aggoun Nassima
* Mazzi Rayene Chorouk

## 🎓 Academic Information

**University of Mohamed Kheider – Biskra**
**Course:** Programming
**Level:** PhD Students
**Academic Year:** 2025/2026

---

## ✨ Features

* ➕ Add a new task
* 📄 View all tasks
* ✔ Mark a task as completed
* 💾 Automatic save to `tasks.json`
* 🔄 Load tasks when program starts
* ⚠ Error handling for invalid input

---

## 🧰 Requirements

* 🐍 Python 3.x
* 📦 No external libraries required

---

## ▶ How to Run

Open a terminal inside the project folder and run:

```bash
python tasks.py
```

---

## 📌 Menu Options

1️⃣ Add task
2️⃣ View tasks
3️⃣ Mark task as done
4️⃣ Exit

---

## 🗂 File Structure

```
task_manager/
│
├── tasks.py        # Main program
├── tasks.json      # Task storage
└── README.md       # Documentation
```

---

## 🖥 Example Output

```
--- Task Manager ---
1. Add task
2. View tasks
3. Mark task as done
4. Exit
```

---

## 🧾 Data Storage Format

Tasks are stored in JSON format:

```json
{
    "title": "Finish assignment",
    "done": false
}
```

---

## 📝 Notes

* The program automatically creates the task list if it does not exist
* Invalid inputs are handled safely
* The application runs entirely in the terminal

---

## 👥 Authors

* Aggoun Nassima
* Mazzi Rayene Chorouk


