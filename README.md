# Customer360 - Customer Communication Management System

A Django-based Customer Relationship Management (CRM) application developed as part of the **IBM Full Stack Software Developer Professional Certificate**. This project demonstrates the development of a centralized customer communication management system that stores and tracks customer interactions efficiently.

> **Note:** This project was completed as part of an IBM guided lab. I implemented the application, configured the project, completed the required features, and successfully ran the application as part of the hands-on learning experience.

---

## Overview

Customer360 is a web application designed to help organizations maintain customer communication records in a centralized platform.

The application enables users to:

- Manage customer information
- Record customer communications
- Track inbound and outbound interactions
- View customer interaction history
- Maintain a professional customer management interface

---

## Features

### Customer Management

- Create new customer records
- View all customers
- Edit customer details
- Store customer information including:
  - Name
  - Email
  - Phone Number
  - Address
  - Social Media

### Communication Records

Each customer interaction stores:

- Communication Channel
- Direction (Inbound / Outbound)
- Summary of interaction
- Date of communication

### Interaction Dashboard

- Display communication history
- Show interactions from the last 30 days
- Easy navigation between customers and communication records

### User Interface

- Responsive HTML templates
- Clean CSS styling
- Django Template Engine
- Simple and intuitive navigation

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Backend Programming |
| Django | Web Framework |
| SQLite3 | Database |
| HTML5 | Frontend Structure |
| CSS3 | Styling |
| Django ORM | Database Operations |
| Git | Version Control |
| GitHub | Repository Hosting |

---

## Project Structure

```
customer360/
│
├── customer360/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── static/
│   └── css/
│       └── main.css
│
├── templates/
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/debayan66/customer360.git
```

Move into the project directory

```bash
cd customer360
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install django
```

Run migrations

```bash
python manage.py migrate
```

Start the development server

```bash
python manage.py runserver
```

Open your browser

```
http://127.0.0.1:8000/
```

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Django project structure
- Django Models
- Django Views
- URL Routing
- Django Templates
- Static Files
- HTML Forms
- CRUD Operations
- Database migrations
- Git and GitHub workflow

---

## Future Improvements

- User Authentication
- Role-based Access Control
- PostgreSQL integration
- Customer search and filtering
- Communication analytics dashboard
- REST API using Django REST Framework
- Email integration
- File attachments for communications
- Pagination
- Docker deployment

---

## Screenshots

You can add screenshots here.

Example:

```
screenshots/
├── homepage.png
├── customer-list.png
├── interaction-form.png
```

---

## Repository

GitHub Repository:

https://github.com/debayan66/customer360

---

## Acknowledgements

This project was completed as part of the **IBM Full Stack Software Developer Professional Certificate** on Coursera.

The project is based on an IBM guided lab designed to provide hands-on experience with Django web development and customer management applications.

---

## Author

**Debayan Nath**

B.Tech in Cyber Security Engineering

GitHub: https://github.com/debayan66

---
