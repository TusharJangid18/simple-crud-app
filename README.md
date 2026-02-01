📌 Project Overview

This project is a simple running web application developed as part of an assessment.
It demonstrates user authentication and CRUD (Create, Read, Update, Delete) operations using a clean and minimal tech stack.

The goal of the project is to show:

Working authentication

End-to-end CRUD functionality

Proper project structure

Clean, readable code

Correct Git usage

Basic testing practices

The UI is intentionally kept simple to focus on functionality, correctness, and clarity, as per the assessment guidelines.

🎯 Key Features
🔐 Authentication

User Registration (Sign Up)

User Login

Secure password hashing

Session-based authentication

Access control (dashboard not accessible without login)

📝 CRUD Operations

After login, the user can:

Create a new task

View a list of tasks

Edit an existing task

Delete a task

Each user can only see and manage their own data.

🗄 Database

SQLite database

Lightweight and file-based

Automatically created on first run

🧪 Testing

Automated test cases using pytest

Covers authentication and CRUD flows

Ensures application reliability

🛠 Technology Stack
Layer	Technology
Backend	Python
Framework	Flask
ORM	Flask-SQLAlchemy
Database	SQLite
Authentication	Session-based
Password Security	Werkzeug
Testing	Pytest
Deployment	Gunicorn + Render
Version Control	Git & GitHub
📂 Project Structure
simple-crud-app/
│
├── app.py                  # Main application file
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
├── test_cases.md           # Manual test cases
├── screenshots_checklist.md
│
├── instance/
│   └── app.db              # SQLite database (auto-generated)
│
├── templates/              # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── edit.html
│
├── static/
│   └── style.css           # Basic styling
│
└── tests/
    └── test_app.py         # Automated test cases

⚙️ Setup Instructions (Local)
1️⃣ Prerequisites

Make sure you have:

Python 3.x installed

Git installed

Verify:

python --version
git --version

2️⃣ Clone the Repository
git clone https://github.com/TusharJangid18/simple-crud-app.git
cd simple-crud-app

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py


Open in browser:

http://127.0.0.1:5000
