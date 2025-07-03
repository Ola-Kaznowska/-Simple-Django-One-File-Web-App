# -Simple-Django-One-File-Web-App
 Simple Django One-File Web App.

# 🌐 Simple Django One-File Web App

## 📖 Project Description

This is a **minimalistic web application** built with Django, written entirely in a **single Python file**. It demonstrates:

- Basic **user login via HTML form** (no JSON or API).
- In-memory item list that can be **viewed and extended**.
- **No database**, no templates, no frontend frameworks — only raw Django + HTML rendering.

Perfect for:
- Beginners learning Django
- Quick demos or proof-of-concepts
- Teaching how HTTP forms and routing work in Django

---

## ⚙️ Features

- 🔐 `/login`: Basic login form using hardcoded credentials (`admin` / `secret`)
- 📦 `/items`: Displays list of items (in memory)
- ➕ `/add`: Add new item via HTML form
- 💡 Written in one single file — `SimpleWebApp.py`

---

## 🧰 Requirements

- Python **3.13.5**
- Django
- Visual Studio Code (recommended)

---

## 💻 Setup Instructions

### 1. ✅ Install Python 3.13.5

Download and install from:

🔗 https://www.python.org/downloads/release/python-3135/

Be sure to:
- Check **"Add Python to PATH"** during installation
- Confirm with:

bash
python --version


# 2. 💼 Install Visual Studio Code (Optional but Recommended)
Download from:

# 🔗 https://code.visualstudio.com/


# 3. 🧩 Install VSC Extensions
Install these extensions in Visual Studio Code:

Python by Microsoft
# 🔗 https://marketplace.visualstudio.com/items?itemName=ms-python.python

(Optional) Pylance
# 🔗 https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance

# 3. Open your browser:
🔐 Login:
# http://127.0.0.1:8000/login
# Username: admin
# Password: secret

📦 Item list:
# http://127.0.0.1:8000/items

➕ Add item:
# http://127.0.0.1:8000/add
