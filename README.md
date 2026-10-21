# 💊 Medicine Reminder

A simple and user-friendly web application that helps users manage their medicines and keep track of their medication schedules.

## ✨ Features

- 🔐 **User Registration & Login** — Create an account and log in securely.
- 💊 **Add Medicines** — Enter medicine details and schedule.
- 📋 **View Scheduled Medicines** — See your saved medicines in one place.
- ✏️ **Edit Medicines** — Update existing medicine information.
- 🗑️ **Delete Medicines** — Remove medicines when they are no longer needed.
- 📊 **Dashboard** — View and search your medicine records.
- 🔒 **User-specific Records** — Users can access their own medicine data.
- 💬 **Flash Messages** — Get feedback after performing actions.

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Database:** SQLite
- **Authentication:** Password hashing with Werkzeug

## 📁 Project Structure

```text
medicine-reminder/
├── app.py
├── create_users.py
├── update_database.py
├── requirements.txt
├── .gitignore
├── static/
│   ├── script.js
│   └── style.css
└── templates/
    ├── dashboard.html
    ├── edit.html
    ├── index.html
    ├── login.html
    └── register.html
```

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/richakumari07/medicine-reminder.git
cd medicine-reminder
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Start the application

```bash
python app.py
```

Open your browser and visit:

`http://127.0.0.1:5000`

## 🔐 Security Notes

- Passwords should be stored as hashes, not plain text.
- Keep secret keys and credentials out of public repositories.
- Do not upload database files containing personal information.
- Configure a strong secret key before deploying the application.

## 🎯 Project Objective

The objective of this project is to provide a convenient way to organize medicine schedules and manage medicine records through a simple web interface.

## 👩‍💻 Author

**Richa Kumari**

GitHub: [@richakumari07](https://github.com/richakumari07)

---

*Built with Python, Flask, HTML, CSS, and JavaScript.*
