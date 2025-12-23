
# Django E-Commerce Website (Ongoing)
## Overview

A full-stack e-commerce web application built using Django.
The project focuses on building a scalable backend, secure user authentication, and core e-commerce functionalities such as product management, cart handling, and order processing.

This project is being developed to gain hands-on experience with backend development, databases, and full-stack workflows.

## Objectives

- Understand how real-world web applications are structured

- Implement secure authentication and authorization

- Design relational database models for e-commerce

- Learn Django’s ORM, views, templates, and admin panel

- Practice clean code, version control, and documentation

## Project Status

Status: 🛠️ Ongoing
Actively being developed and improved.

## Planned Features
### User Features

- User registration and login

- User-specific shopping cart

- Order history per user

- Secure authentication

### Product & Store

- Product listing with categories

- Product detail pages

- Add to cart / remove from cart

- Quantity updates

### Orders & Checkout

- Order creation and tracking

- Cart persistence using database

- Admin-managed order status

### Admin Panel

- Manage products and categories

- Manage users and orders

- Use Django Admin interface

## Tech Stack
### Backend

Python

Django

### Frontend

HTML

CSS

JavaScript (basic)

### Database

SQLite (development)

PostgreSQL (planned)

### Tools

Git & GitHub

VS Code


## Project Structure (Planned)
django-ecommerce/
│
├── ecommerce/        # Main project settings
├── store/            # Product & category app
├── accounts/         # User authentication
├── cart/             # Cart functionality
├── orders/           # Order processing
├── templates/        # HTML templates
├── static/           # CSS & JS files
├── db.sqlite3
└── manage.py

## Installation & Setup (Local)
1️⃣ Clone the Repository
git clone https://github.com/FaizAkram19/django-ecommerce.git
cd django-ecommerce

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install django

4️⃣ Run Migrations
python manage.py migrate

5️⃣ Start Development Server
python manage.py runserver


Open browser and visit:

http://127.0.0.1:8000/

## Learning Outcomes

Hands-on experience with Django framework

Understanding MVC / MVT architecture

Writing database-backed web applications

Implementing authentication and authorization

Managing real-world project structure

## Future Enhancements

Payment gateway integration

REST API using Django REST Framework

Frontend redesign

Deployment on cloud (AWS / Render / Railway)

Docker support

## Contributing

This is a personal learning project.
Suggestions and feedback are welcome.

## Author
Faiz Akram  
B.Tech Computer Science Student  
GitHub: https://github.com/FaizAkram19


