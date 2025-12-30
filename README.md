# 📋 Todo List Application

A simple **Todo List Web Application** built using **Python and Django**.  
This project helps users manage daily tasks by adding, viewing, updating, and deleting todos.

---

## 🚀 Features

- ➕ Add new tasks  
- 📄 View all tasks  
- ✏️ Update tasks  
- ❌ Delete tasks  
- 🛠 CRUD operations using Django  
- 💾 SQLite database  

---

## 🛠 Technologies Used

- Python  
- Django  
- HTML  
- CSS  
- SQLite  

---

## 📁 Project Structure

Todo-list/
│
├── todo_project/ # Main Django project
├── todo_app/ # Todo application
├── templates/ # HTML templates
├── static/ # CSS files
├── db.sqlite3 # Database
├── manage.py
└── requirements.txt


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/tanayakamble2001/Todo-list.git
cd Todo-list

### 2️⃣ Create a virtual environment
```bash
python -m venv venv
Activate it:

### Windows
```bash
venv\Scripts\activate

### Linux / macOS
```bash
source venv/bin/activate

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt

### 4️⃣ Apply migrations
```bash
python manage.py migrate
