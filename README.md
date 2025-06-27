# notes-app-django-react

# 📝 Notes App – Built with Django & React

Hi, I’m Harsha — and this is a **full-stack notes app** I built using Django (DRF) for the backend and React + TailwindCSS for the frontend.

This project was part of my learning journey into building modern full-stack apps, with features like token authentication, note creation, and clean UI design.

---

## 🚀 What It Does

- 🔐 User Login with Token Authentication (via Djoser)
- 📝 Create & Delete Notes
- 💾 Stores token in browser (localStorage)
- 🎨 Simple, clean UI with TailwindCSS

---

## 🧠 Tech Stack

**Backend**:
- Django REST Framework
- Djoser (Token-based Auth)
- SQLite (default DB)

**Frontend**:
- React (Vite)
- Axios (for API requests)
- TailwindCSS

---

## 🛠️ Run This App Locally

### 📦 Backend Setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt  # or install DRF, Djoser manually
python manage.py migrate
python manage.py createsuperuser  # (create your admin user)
python manage.py runserver
