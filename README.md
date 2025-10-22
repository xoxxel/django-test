# Simple Django Educational Project

This is a simple educational project built with Django to demonstrate the basic structure and functionality of a Django application.

## Project Structure

```
simple-django-edu
├── manage.py
├── requirements.txt
├── .gitignore
├── .env
├── README.md
├── project
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── core
│   ├── migrations
│   │   └── __init__.py
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates
│   └── core
│       └── index.html
└── static
    ├── css
    │   └── styles.css
    └── js
        └── main.js
```

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd simple-django-edu
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   Create a `.env` file in the root directory and add your environment variables, such as:
   ```
   SECRET_KEY=your_secret_key
   DEBUG=True
   ```

5. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the application:**
   Open your browser and go to `http://127.0.0.1:8000/`.

## Usage

This project serves as a basic template for building Django applications. You can modify the models, views, and templates to suit your educational needs.