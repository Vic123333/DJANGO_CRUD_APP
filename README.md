# Django CRUD Application with SQLite

This is a Django-based web application that provides full CRUD (Create, Read, Update, Delete) functionality, along with user authentication features like registration and login. The app is built using Django's built-in templating system for rendering HTML and styled with Tailwind CSS for a modern, responsive design. It uses SQLite as its database.

## Features

- **CRUD Operations**: Perform create, read, update, and delete operations on records with a simple and intuitive interface.
- **User Authentication**: Includes secure registration and login functionalities, allowing only authenticated users to perform CRUD operations.
- **Django Templates**: Uses Django's templating engine to render dynamic HTML content, providing a clean and responsive user interface.
- **Tailwind CSS**: The app is styled with Tailwind CSS, offering a modern and fully responsive design out of the box.
- **SQLite Database**: The application uses SQLite, a lightweight and file-based database, for easy deployment and maintenance.

## Screenshots
![DJANGO_CRM](./screenshots/main.PNG)
![DJANGO_CRM](./screenshots/login.PNG)
![DJANGO_CRM](./screenshots/register.PNG)



## Installation

### Prerequisites

- Python 3.10
- Django
- SQLite (included with Python)

### Steps
1. **Clone the repository:**

   ```bash
   git clone https://github.com/Vic123333/DJANGO_CRUD_APP
2. **Add DJANGO_SECRET_KEY to the .env file**
   - Use the randomsecretkey.py to create a secret key and then add it to the DJANGO_SECRET_KEY in the .env file that is located in the myProject folder
3. **Install packages**
   ```bash
   pip install django
   pip install python-dotenv
4. **Apply migrations**
   ```bash
   python manage.py migrate
5. **Create a superuser (admin account)**
   ```bash
   python manage.py createsuperuser
6. **Runserver**
   ```bash
   python manage.py runserver
