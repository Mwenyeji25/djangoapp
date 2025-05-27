🔐 Django Authentication App
DjangoAuthApp is a user authentication system built with Django that provides core user management functionalities, including:

User Signup

User Login

User Logout

Password Reset via Email

Session Management & Access Control

Features
Secure password hashing using Django's built-in authentication system

Middleware support for access restriction

Customizable email verification/reset system

Clear and user-friendly interface for authentication

CSRF and session protection out of the box

Functionality Overview
Feature	Description
Signup	New users can create accounts with email and password
Login	Registered users can authenticate with credentials
Logout	Safely log out of the system
Password Reset	Users can request a reset link via email
Middleware	Restricts access to authenticated sections of the site

⚙️ Technologies Used
Python 3.x

Django 4.x

SQLite/PostgreSQL/MySQL (configurable)

Bootstrap/Tailwind CSS (customizable frontend)

SMTP for email password reset (Gmail/SendGrid etc.)

 Installation
git clone https://github.com/Mwenyeji25/djangoapp.git
cd djangoapp

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt

Create .env with:

SECRET_KEY=your-secret-key
DEBUG=True
EMAIL_HOST_USER=you@example.com
EMAIL_HOST_PASSWORD=yourpassword

Then run:
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

To-Do (Optional)
Add social login (Google, Facebook)

Add two-factor authentication

Improve front-end responsiveness
