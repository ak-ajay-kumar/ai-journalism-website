# 📰 AI Journalism Website for Material Science

An AI-powered journalism platform built with Django, designed for publishing and managing articles in the field of material science. This project allows contributors to submit articles, admins to review and approve content, and integrates real-time news using external APIs.

---

## 🚀 Features

- 🧠 AI-based content assistance and classification
- ✍️ Article submission by registered users
- ✅ Admin panel with approval/rejection tracking
- 📅 Approval history with timestamps and admin details
- 📰 Real-time material science news (via NewsAPI)
- 🔒 Secure user authentication and role-based access
- 📁 PDF uploads and content downloads
- 🎨 Clean, professional frontend UI (HTML/CSS/JS)

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: SQLite3 / PostgreSQL

---

## 📦 Folder Structure

ai-journalism-website/
├── manage.py
├── templates/
├── static/
├── media/
├── app_name/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── ...
├── docs/
│ └── AI_Journalism_Project_Report.pdf
└── README.md


---

## ⚙️ How to Run the Project Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ak-ajay-kumar/ai-journalism-website.git
   cd ai-journalism-website

    Create and activate virtual environment:

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py makemigrations
python manage.py migrate

Start the server:

python manage.py runserver

Visit http://127.0.0.1:8000/ in your browser
