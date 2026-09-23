# University Attendance Management System

Cloud-based university attendance management system built with Flask, MySQL, HTML, CSS, JavaScript and Bootstrap.

## Planned roles
- Admin
- Faculty
- Student

## Local setup
1. Create and activate a Python virtual environment.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and update database credentials.
4. Create the MySQL database using `database/schema.sql`.
5. Run:
   `python app.py`

## Cloud deployment
The application is intended to be deployed later using:
- AWS EC2 for the Flask application
- AWS RDS MySQL for the database
