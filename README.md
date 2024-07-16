# Backend Modules

This project contains reusable backend modules for Django applications. Currently, it includes a basic authentication module.

## Current Features

- Custom User model
- User registration functionality

## Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment: 
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
4. Install dependencies: `pip install django djangorestframework`
5. Run migrations: `python manage.py migrate`
6. Run the development server: `python manage.py runserver`

## Running Tests

To run tests, use the following command:
`python manage.py test authentication`