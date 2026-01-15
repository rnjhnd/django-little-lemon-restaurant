# Little Lemon Restaurant Website

A dynamic web application built with **Django** as part of the **Meta Django Web Framework** course. This project focuses on implementing a modular front-end using the Django Template Language (DTL) and managing restaurant data through a robust back-end.

## 🚀 Key Features
* **Template Inheritance:** Utilized a `base.html` skeleton to ensure consistent layout across the About, Menu, and Booking pages.
* **Modular Components:** Created reusable partials for the header and footer to simplify maintenance.
* **Dynamic Data Rendering:** Used Django QuerySets and DTL `for` loops to display menu items dynamically from a database.
* **Secure Forms:** Implemented CSRF protection on all user input forms to ensure secure data submission.
* **Class-Based Views:** Leveraged `ListView` for efficient, extensible, and reusable code structure.

## 🛠️ Technologies Used
* **Framework:** Django 4.1.3
* **Language:** Python 3.8
* **Database:** SQLite (Development) / MySQL (Production-ready)
* **Frontend:** HTML5, CSS3, Django Template Language

## 📂 Project Structure
```text
assets/
workspace/
└── littlelemon/
    ├── littlelemon/                 # Django project configuration
    │   ├── __pycache__/             # Auto-generated Python bytecode
    │   ├── __init__.py              # Python package marker
    │   ├── asgi.py                  # ASGI entry point
    │   ├── settings.py              # Project settings
    │   ├── urls.py                  # Root URL configuration
    │   └── wsgi.py                  # WSGI entry point
    ├── restaurant/                  # Main Django application
    │   ├── __pycache__/             # Auto-generated Python bytecode
    │   ├── migrations/              # Database migrations
    │   ├── static/                  # Static assets (CSS, JS, images)
    │   ├── templates/               # HTML templates
    │   ├── __init__.py              # App package marker
    │   ├── admin.py                 # Django admin configuration
    │   ├── apps.py                  # App configuration
    │   ├── forms.py                 # Django forms
    │   ├── models.py                # Database models
    │   ├── tests.py                 # Unit tests
    │   ├── urls.py                  # App URL routing
    │   └── views.py                 # View logic
    ├── db.sqlite3                   # SQLite database
    ├── manage.py                    # Django management script
    └── Final Assessment.md          # Project documentation
```

## ⚙️ Installation and Setup
1. Clone the repository:
   
   ```bash
   git clone https://github.com/your-username/little-lemon-django-web.git
   ```
   
2. Navigate to the project directory:
   
   ```bash
   cd little-lemon-django-web
   ```

3. Install dependencies:

   ```bash
   pip install django mysqlclient
   ```
   
4. Run migrations:

   ```bash
   python3 manage.py makemigrations
   python3 manage.py migrate
   ```

5. Create a superuser (Admin access):

   ```bash
   python3 manage.py createsuperuser
   ```

6. Start the development server:

   ```bash
   python3 manage.py runserver
   ```

---

The site will be available at http://127.0.0.1:8000/
