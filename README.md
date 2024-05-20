# Django Todo List App Tutorial

This repository contains the source code for a Todo List web application built using Django. The application allows users to view completed and not completed tasks, and tasks can only be added from the admin interface.

## Tutorial Video
To follow along with the development of this Todo List app, watch the tutorial video on YouTube: [Django Todo List App Tutorial](https://www.youtube.com/watch?v=nGIg40xs9e4&t=423s)

## Features
- View completed and not completed tasks
- Add new tasks from the admin interface
- Edit existing tasks from the admin interface
- Delete tasks from the admin interface
- User-friendly interface

## Requirements
- Python
- Django

## Setup
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Apply migrations:
    ```
    python manage.py migrate
    ```
4. Create a superuser for accessing the admin interface:
    ```
    python manage.py createsuperuser
    ```
5. Run the development server:
    ```
    python manage.py runserver
    ```
6. Visit http://localhost:8000/admin and log in with the superuser credentials to add tasks.

7. Visit http://localhost:8000/todos to views tasks and their status.
