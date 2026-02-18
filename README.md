\# FlaskAuthApp



A simple Flask Authentication application with \*\*secure user registration and login\*\*.



\## Features

\- User Registration with server-side validation

\- Login authentication with hashed passwords (bcrypt)

\- Email uniqueness check

\- Session-based authentication

\- Error handling using Flask flash messages



\## Validation Rules

\### Registration

\- Name cannot be empty

\- Email cannot be empty

\- Password must be at least 6 characters

\- Email must be unique



\### Login

\- Email and password are required

\- Invalid credentials are handled securely



\## Tech Stack

\- Python

\- Flask

\- Flask-SQLAlchemy

\- SQLite

\- Bcrypt

\- HTML + Bootstrap



\## How to Run Locally

```bash

pip install -r requirements.txt

python app.py



