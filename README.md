# Student Management System

A Django-based web app to manage student records, parent info, and authentication for schools.

## Overview

Built this project to handle basic school administration tasks - adding students, managing their details, parent information, and user authentication with password reset functionality.

## Tech Stack

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** PostgreSQL / SQLite
- **Containerization:** Docker

## Features

- Student CRUD operations (add, edit, view, delete)
- Student dashboard with search and filters
- Parent details management
- User authentication (login, register, forgot password)
- Responsive UI design

## Quick Setup

```bash
# Clone the repo
git clone https://github.com/PanugothuSricharan/Student-Management-System.git
cd Student-Management-System

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
```

Open `http://localhost:8000` in your browser.

## Docker Setup

```bash
docker-compose up --build
```

## Project Structure

```
├── Home/           # Main Django settings
├── home_auth/      # Authentication (login, register, password reset)
├── school/         # School related models
├── student/        # Student & parent management
├── templates/      # HTML templates
├── static/         # CSS, JS, images
└── manage.py
```

 
