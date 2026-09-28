# 📔 Personal Journal Manager

A simple **Python command-line Personal Journal Manager** that lets you create, view, search, and delete journal entries. 🐍✨

## 🌟 Features

- ➕ **Add a New Entry** — Save a journal entry with the current date and time.
- 📖 **View All Entries** — Display all saved journal entries.
- 🔍 **Search for an Entry** — Search entries using a keyword or date.
- 🗑️ **Delete All Entries** — Delete the complete journal file after confirmation.
- 🚪 **Exit** — Safely exit the application.
- 💾 Journal data is stored in a local `journal.txt` file.

## 🛠️ Technologies Used

- 🐍 Python
- 📁 File Handling
- 🕒 `datetime`
- 💻 Command Line Interface (CLI)
- 🔎 String Searching
- 🗂️ `os` module

## 📋 Menu

```text
Welcome to Personal Journal Manager!
Please select an option:

1. Add a New Entry
2. View All Entries
3. Search for an Entry
4. Delete All Entries
5. Exit
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### 2. Open the project

```bash
cd <YOUR-PROJECT-FOLDER>
```

### 3. Run the Python file

```bash
python "PROJECT 6.py"
```

> 💡 Make sure Python is installed on your computer.

## 🧠 How It Works

### 1️⃣ Add a New Entry
The program asks for your journal text and automatically adds a timestamp. The entry is saved in `journal.txt`.

### 2️⃣ View All Entries
The program reads `journal.txt` and displays all available journal entries.

### 3️⃣ Search for an Entry
Enter a keyword or date. The program searches the saved entries without considering uppercase/lowercase differences.

### 4️⃣ Delete All Entries
The program asks for confirmation before deleting the journal file.

### 5️⃣ Exit
The application displays a goodbye message and closes.

## 📸 Screenshots

### ➕ Add a New Entry
![Add New Entry](screenshots/screenshot-1.png)

### 📖 View All Entries
![View All Entries](screenshots/screenshot-2.png)

### 🔍 Search for an Entry
![Search Entry](screenshots/screenshot-3.png)

### 🗑️ Delete All Entries
![Delete All Entries](screenshots/screenshot-4.png)

### 🚪 Exit
![Exit](screenshots/screenshot-5.png)

## 📁 Project Structure

```text
Personal-Journal-Manager/
│
├── 📄 PROJECT 6.py
├── 📄 README.md
└── 📁 screenshots/
    ├── 🖼️ screenshot-1.png
    ├── 🖼️ screenshot-2.png
    ├── 🖼️ screenshot-3.png
    ├── 🖼️ screenshot-4.png
    └── 🖼️ screenshot-5.png
```

## 💾 Data File

When you add your first journal entry, the program creates:

```text
journal.txt
```

Example:

```text
[2026-09-28 11:54:57]
TODAY I AM VERY HAPPY
```

## 🎯 Learning Outcomes

This project demonstrates:

- 🐍 Python functions
- 🔁 `while` loop
- 🔀 `if / elif / else`
- 📂 File read/write operations
- 🕒 Date and time handling
- 🔍 Searching text
- 🗑️ File deletion
- ⚠️ Basic error handling
- 🧩 Menu-driven programming

## 👨‍💻 Project

**Personal Journal Manager**  
Built with ❤️ using Python 🐍

---

⭐ If you found this project useful, consider giving the repository a star!
