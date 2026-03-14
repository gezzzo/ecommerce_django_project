# Ecommerce Django Project

A complete **Django ecommerce project** built end-to-end, covering products, user accounts, templates, static assets, media handling, and core store functionality.

## Overview

This project is a practical ecommerce web application built with **Django**.  
It is designed as part of a step-by-step series to demonstrate how to build a real-world online store from scratch using Django.

The project structure includes dedicated apps for account management and product handling, along with templates, static files, and media support.

## Features

- Product listing
- Product detail pages
- Account system
- Template-based frontend
- Static and media file handling
- Organized Django project structure
- Scalable foundation for cart and checkout features

## Tech Stack

- Python
- Django
- HTML
- CSS
- JavaScript
- SQLite

## Project Structure

```bash
ecommerce_django_project/
│
├── account/
├── ecommerce/
├── product/
├── media/
├── static/
├── templates/
├── manage.py
└── db.sqlite3
```


## Run Locally
1. Clone the repository
```bash
git clone https://github.com/gezzzo/ecommerce_django_project.git
cd ecommerce_django_project
```

2. Create and activate a virtual environment:

```bash
# Windows
python -m venv venv
venv\Scripts\activate
# Mac / Linux
python3 -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Apply migrations

```bash
python manage.py migrate
```

5. Run the development server
```bash
python manage.py runserver
```
