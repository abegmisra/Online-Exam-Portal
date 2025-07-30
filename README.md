
# Online Examination Portal

A full-stack web application built using the Django framework that enables teachers to create online exams and students to participate in them. It includes role-based dashboards, real-time result evaluation, and a simple, user-friendly interface.

## Features

### Teacher Panel
- Create and manage courses and exams
- Add multiple-choice questions
- View student submissions and results

### Student Panel
- Register and log in
- Take exams assigned to them
- View results instantly

### Admin Panel
- Access Django's built-in admin dashboard
- Manage users, courses, questions, and results

## Technology Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default)
- **Authentication**: Django's built-in auth system
- **Image Handling**: Pillow library

## Getting Started

To run the project locally:

```bash
# Clone the repository
git clone <your-repo-url>
cd onlinexamination

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Run database migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Start the development server
python manage.py runserver
