# 🚀 TaskFlow – Task Management System

TaskFlow is a modern web-based task management application built using HTML, CSS, and Vanilla JavaScript.
It helps users create, organize, and track daily tasks efficiently.

All tasks are stored using the browser’s LocalStorage, so they remain available even after refreshing the page.


## ⚙️ How It Works

1. Users create tasks using the input form  
2. Tasks are stored in LocalStorage  
3. JavaScript dynamically renders tasks on the page  
4. Users can filter, search, edit, and reorder tasks  
5. Statistics and progress update automatically


## ✨ Features

### 📝 Task Management
- ➕ Add new tasks
- ✏️ Edit tasks
- 🗑 Delete tasks
- ✅ Mark tasks as completed
- 📝 Add notes to tasks
- 🔀 Drag and reorder tasks

### ⚡ Priority Levels
Tasks can be assigned different priority levels:

- 🔴 High Priority
- 🟡 Medium Priority
- 🟢 Low Priority

High priority tasks are visually highlighted to help users focus on important work.

### 🏷 Task Categories
Tasks can be organized into different categories:

- 💼 Work
- 🌿 Personal
- 📚 Study
- ❤️ Health
- 📌 Other

This helps users organize tasks based on their purpose.

### 📅 Due Date & Deadline Tracking
Users can assign due dates to tasks.

The application automatically:
- ⚠️ Detects overdue tasks
- 🚨 Highlights overdue items
- ⏰ Displays reminders for pending tasks

### 🔍 Search and Filtering
Users can quickly find tasks using:

Search
- 🔎 Search tasks by name or notes

Filters
- 📋 All tasks
- 🟢 Active tasks
- ✅ Completed tasks
- ⏰ Overdue tasks
- 🔴 High priority tasks

### ⭐ Productivity Rewards
To motivate users, TaskFlow includes a reward system.

When a task is completed:
- ⭐ A star reward is earned
- 🎉 A celebration popup appears
- 🦆 Overdue tasks show a reminder popup

This system encourages users to stay productive.

### 📝 Task Notes
Each task supports additional notes where users can store:
- Extra details
- Instructions
- Reminders

### 🔀 Drag & Drop Reordering
Tasks can be reordered by dragging and dropping, allowing users to manually prioritize tasks.


### 📊 Progress Tracking
TaskFlow provides real-time statistics such as:
- 📋 Total tasks
- ✅ Completed tasks
- ⏰ Overdue tasks
- 🔴 High priority tasks
- ⭐ Stars earned

A progress bar visually shows the task completion percentage.

### 🎨 Theme Support
TaskFlow supports two themes:
- 🌙 Dark Mode
- ☀ Light Mode

Users can switch between themes easily.

### 💾 Data Persistence
All tasks are saved using the browser's LocalStorage, which means:
- No backend server is required
- Tasks remain saved after refresh
- The app works offline

### 📤 Export & Import
Users can create backups of their tasks.

Export
- 📦 Tasks can be exported as a JSON file.

Import
- 📥 Users can import tasks later to restore their data.


## 🛠 Technologies Used
- 🧱 HTML5
- 🎨 CSS3
- ⚙️ JavaScript (Vanilla)
- 💾 LocalStorage API
- 🔄 DOM Manipulation


## 📁 Project Structure

TaskFlow/
│
├── project.html
└── README.md

The entire application including UI, styling, and logic is contained in a single HTML file.


## 📦 Task Data Structure

Each task is stored as a JavaScript object:

{
  id: 123456789,
  text: "Complete project report",
  completed: false,
  priority: "high",
  category: "work",
  due: "2026-03-10T18:00",
  notes: "",
  starred: false
}


