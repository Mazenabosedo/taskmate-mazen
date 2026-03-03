# TaskMate 📝

TaskMate is a web-based task management application built using Django and PostgreSQL.  
It allows users to create, update, and manage their daily tasks efficiently.

## 🚀 Features
- User authentication (Register / Login / Logout)
- Create, edit, and delete tasks
- Mark tasks as completed
- Task ownership (each user manages their own tasks)
- PostgreSQL database integration
- Deployment-ready (Railway)

## 🛠 Technologies Used
- Python
- Django
- PostgreSQL
- HTML / CSS
- Bootstrap
- Gunicorn
- Railway (Deployment)

## 📦 Installation

```bash
git clone https://github.com/yourusername/taskmate.git
cd taskmate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
