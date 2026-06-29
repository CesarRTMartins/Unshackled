# Unshackled

A web application developed with **Django** and **MySQL**, designed to provide a secure and scalable platform with user authentication and database-driven functionality. This project demonstrates full-stack web development using Python and the Django framework.

## Features

* User authentication and authorization
* Django Admin dashboard
* MySQL database integration
* Responsive web interface
* CRUD operations for application data
* Secure backend using Django's built-in security features
* Session management and user login system

## Tech Stack

* Python
* Django
* MySQL
* HTML5
* CSS3
* JavaScript

## Installation

### Clone the repository

```bash
git clone <repository-url>
```

### Navigate to the project

```bash
cd Unshackled/pap
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

## Database Configuration

Configure your MySQL connection in:

```
pap/settings.py
```

Update the database credentials with your own MySQL server information.

After configuring the database, run:

```bash
python manage.py migrate
```

## Create an Administrator (Optional)

```bash
python manage.py createsuperuser
```

Follow the prompts to create an administrator account.

## Running the Application

Start the development server:

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

The Django administration panel is available at:

```
http://127.0.0.1:8000/admin/
```

## Project Structure

```
Unshackled/
├── pap/
│   ├── manage.py
│   ├── pap/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   └── ...
├── README.md
└── requirements.txt
```

## Learning Objectives

This project was developed to strengthen knowledge in:

* Django web development
* MVC (Model-View-Template) architecture
* MySQL database integration
* User authentication and authorization
* Backend routing and request handling
* Database migrations
* Secure web application development

## Future Improvements

* REST API integration
* Role-based access control
* Email verification
* Password recovery
* Docker support
* Automated testing
* CI/CD pipeline
* Improved frontend styling

## Author

**César Martins**

---

This project was developed as part of my learning journey in backend and full-stack web development, with a focus on building secure and scalable applications using Django.
