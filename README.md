# 📇 Contact Management System 

A desktop-based **Contact Management System** built using **Python** and **SQL**. This application provides a simple GUI to **add, view, update, and delete contacts**, with data stored locally in an SQL database.

---


## ✨ Features

* ➕ Add new contacts
* ✏️ Update existing contacts
* ❌ Delete contacts with confirmation
* 📋 View all contacts in a table
* 🖱️ Double‑click a contact to edit
* 💾 Automatic database creation

---

## 🖥️ Application Overview

### Main Window

* Displays all contacts in a table
* **Add New** button to insert contacts
* **Delete** button to remove selected contacts

### Add / Update Window

* Fields:

  * Firstname
  * Lastname
  * Gender
  * Age
  * Address
  * Contact
* Gender selection using radio buttons
* Save or Update functionality

---

## 🗄️ Database Details

The application uses an SQLite database named **`contact.db`**.

### Table: `member`

```
mem_id   INTEGER  PRIMARY KEY AUTOINCREMENT
firstname TEXT
lastname  TEXT
gender    TEXT
age       TEXT
address   TEXT
contact   TEXT
```

The database and table are created automatically when the application runs for the first time.

---

## 🚀 How to Run

### 1️⃣ Requirements

* Python 3.x installed on your system

Check Python version:

```bash
python --version
```

---

### 2️⃣ Run the Application

```bash
python main.py
```

> Replace `main.py` with the actual filename if different.

---

## 🧠 How It Works

* On startup, the app initializes the SQLite database
* Contact records are loaded into a Treeview table
* Double‑clicking a record opens the update window
* All CRUD operations are synced with the database

---

## ⚠️ Notes

* All fields are required when adding or updating contacts
* Age should be entered as a numeric value
* `contact.db` will be created in the project directory

---

## 📄 License

This project is open‑source and intended for educational and personal use.
