📚 StudyBuddy – Learning Management System
StudyBuddy is a full-featured web-based Learning Management System (LMS) built using Python Django. It allows teachers to manage courses, upload assignments, and track student progress, while students can enroll in courses, submit assignments, and view performance reports – all through a clean, responsive interface.

🚀 Features
👤 Role-based login system (Teacher & Student)

📚 Course and assignment management

📝 Student assignment submission and evaluation

📊 Progress tracking dashboards

🎨 Responsive UI using Django templates

🔐 Secure authentication & session management

🛠️ Tech Stack
Layer	Technology
Backend	Python, Django
Frontend	HTML, CSS, Bootstrap
Database	SQLite (default Django DB)
Tools Used	Git, GitHub

📷 Screenshots
(Add relevant screenshots here for Home Page, Teacher Dashboard, Student View, etc.)

🏁 Getting Started
Prerequisites
Python 3.x

Django

pip (Python package manager)

Git

Installation
# Clone the repository
git clonehttps://github.com/Shreyas-7083/StudyBuddy.git

# Navigate into the project directory
cd studybuddy

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver

👥 User Roles
Teacher

Create and manage courses

Upload and evaluate assignments

View student progress

Student

Enroll in courses

Submit assignments

View grades and feedback

📂 Project Structure
studybuddy/
├── manage.py
├── studybuddy/         # Django project settings
├── lms/                # Main LMS app
│   ├── templates/
│   ├── views.py
│   ├── models.py
│   ├── urls.py
│   └── ...
└── static/

🙋‍♂️ Author
Shreyas Gopale
📧 shreyasgopale2@gmail.com
