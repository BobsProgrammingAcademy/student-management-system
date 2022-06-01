# Student Management System

This is a student management system built using **Django 4** and **Bootstrap 5**.

![plot](https://github.com/BobsProgrammingAcademy/Student-Management-System/blob/master/students/static/images/homepage.png?raw=true)

## Prerequisites

Install the following prerequisites:

1. [Python](https://www.python.org/downloads/)
2. [Visual Studio Code](https://code.visualstudio.com/download)


## Installation

### 1. Create a virtual environment

From the **root** directory run:

```bash
python -m venv venv
```

### 2. Activate the virtual environment

From the **root** directory run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

### 3. Install required dependencies

From the **root** directory run:

```bash
pip install -r requirements.txt
```

### 4. Run migrations

From the **root** directory run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

## Run the application

From the **root** directory run:

```bash
python manage.py runserver
```

## View the application

Go to http://127.0.0.1:8000/ to view the application.