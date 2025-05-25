# Technical Service Allocation System

A web-based application built with **Python** and **Django** to manage and allocate technical service requests efficiently. The system allows users to submit service issues and enables admins to assign available technicians and track the status of each request.

## 🔧 Features

- Submit new technical service requests
- View all service requests in a dashboard
- Assign technicians to pending service issues
- Track request status and assigned technician
- Fully functional CRUD operations
- Uses Django ORM for database interaction

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite (can be switched to MySQL)
- **Architecture:** MVT (Model-View-Template)

## 📁 Project Structure
service_project/
├── service_allocation/ # Django project folder (settings, URLs)
├── allocations/ # App for managing services and technicians
│ ├── models.py # Database models
│ ├── views.py # Business logic
│ ├── forms.py # Django forms
│ ├── templates/ # HTML templates
│ └── urls.py # App routing
└── manage.py



## 🚀 Getting Started

1. **Clone the repository:**
   git clone https://github.com/yourusername/service-allocation-system.git
   cd service-allocation-system

   
3. **Set up a virtual environment (optional but recommended)**:

#
```python
python -m venv env
env\Scripts\activate    # On Windows
source env/bin/activate # On Linux/Mac
```
4.**Install dependencies:**
```python
pip install django
```
5.**Apply migrations:**
```python
python manage.py makemigrations
python manage.py migrate
```

6.**Run the development server:**
```python
python manage.py runserver
```

7.**Access the app:**
Open your browser and go to http://127.0.0.1:8000

