# Gym Membership Management

A simple Gym Member Management Web App built using Django - to keep a track of all Equipment, Plans, Enquires and members

## What it does
1) Allows users to register, log in, and access their gym membership details.
2) Helps admins manage members, including adding, updating, and removing records.
3) Tracks membership plans, subscriptions, and renewal status.
4) Provides a dashboard to view and manage gym-related data easily.
5) Ensures secure access with user authentication and role-based control.

## Tech-Stack

Backend: Python, Django
Frontend: HTML, CSS, JavaScript
Framework Features: Django Templates, Django ORM, Django Admin
Database: SQLite (default Django database)
Authentication: Django built-in authentication system 
Styling/UI: CSS, Bootstrap
Version Control: Git & GitHub

## Architecture 

- Follows a three-layer architecture: Frontend, Backend, and Database.
- Frontend uses HTML, CSS, and JavaScript with Django Templates.
- Backend is built with Django for routing and business logic.
- Handles authentication and sessions using Django’s built-in system.
- Uses SQLite with Django ORM for database operations.
- Includes Django Admin for managing users and gym data.
- Manages static files like CSS, JS, and images through Django.

## Set-Up

1. Clone the repository
2. Create Virtual Environment
```
   python -m venv venv
   venv\Scripts\activate
```
3. Install Dependencies:
```
   pip install -r requirements.txt    
```
4. Run Migrations:
```
   python manage.py migrate   
```
5. Create Superuser (Optional):
```
   python manage.py createsuperuser
```
6. Run the server:
```
   python manage.py runserver
```
(Inspired by existing open-source implementations, extended and customized with additional features and improvement)
