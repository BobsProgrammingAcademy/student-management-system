# Student Management System

This is a student management system built using **Django 4**, **HTML 5**, **CSS 3**, and **Bootstrap 5** with a **Bootswatch** theme.

![plot](https://github.com/BobsProgrammingAcademy/Student-Management-System/blob/master/students/static/images/homepage.png?raw=true)


## Table of Contents 
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Run the application](#run-the-application)
- [Run the tests](#run-the-tests)
- [View the application](#view-the-application)
- [Copyright and License](#copyright-and-license)


### Prerequisites

Install the following prerequisites:

1. [Python 3.8-3.11](https://www.python.org/downloads/)
<br> This project uses **Django v4.2.4**. For Django to work, you must install a correct version of Python on your machine. More information [here](https://django.readthedocs.io/en/stable/faq/install.html).
2. [Visual Studio Code](https://code.visualstudio.com/download)


### Installation

#### 1. Create a virtual environment

From the **root** directory, run:

```bash
python -m venv venv
```

#### 2. Activate the virtual environment

From the **root** directory, run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

#### 3. Install required dependencies

From the **root** directory, run:

```bash
pip install -r requirements.txt
```

#### 4. Run migrations

From the **root** directory, run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

#### 5. Create an admin user to access the Django Admin interface

From the **root** directory, run:

```bash
python manage.py createsuperuser
```

When prompted, enter a username, email, and password.


### Run the application

From the **root** directory, run:

```bash
python manage.py runserver
```


### Run the tests

From the **root** directory, run:

```bash
python manage.py test --pattern="tests.py"

```


### View the application

Go to http://127.0.0.1:8000/ to view the application.


### Copyright and License

Copyright © 2022 Bob's Programming Academy. Code released under the MIT license.
