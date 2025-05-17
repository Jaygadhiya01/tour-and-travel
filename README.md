# 🌍 Tour and Travel Website

A comprehensive travel management platform developed to simplify tour bookings, travel guide assignments, and blog-based traveler engagement. This project was developed as part of the 6th Semester MCA curriculum at L.J. Institute of Computer Applications.

## ✨ Project Highlights

- 🧾 Online tour package booking with real-time availability
- 👤 Admin dashboard to manage packages, destinations, blogs, and users
- 🧭 Travel guide management and assignment
- ⭐ User feedback and review system
- 📰 Blog section to post travel stories
- 🖥️ Responsive UI for mobile and desktop

---

## 🎯 Objectives

- Automate manual booking and reduce processing time by up to 80%
- Provide centralized control for all travel operations
- Enable real-time updates for users and admins
- Improve customer satisfaction and reduce human error

---

## 📌 Features

### For Users:
- Register/Login
- View and book travel packages
- Select or get assigned a travel guide
- Leave reviews and ratings
- Read travel blogs
- Contact agency via form

### For Admin:
- Manage packages, guides, bookings, users, blogs, reviews
- View dashboard analytics
- Update content dynamically without code changes

---

## 🧑‍💻 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Django (Python)
- **Database:** SQLite3
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

```bash
travel_project/
├── accounts/              # User management
├── bookings/              # Tour booking logic
├── guides/                # Guide data and assignment
├── packages/              # Tour packages and destinations
├── blogs/                 # Blog module
├── reviews/               # User reviews
├── contact/               # Contact form handling
├── templates/             # HTML files
├── static/                # CSS, JS, Images
├── db.sqlite3             # Development database
└── manage.py              # Django project manager

# Step 1: Create a virtual environment
python -m venv venv

# Step 2: Activate the virtual environment
# For Windows:
venv\Scripts\activate
# For macOS/Linux:
source venv/bin/activate

# Step 3: Install project dependencies
pip install -r requirements.txt

# Step 4: Apply database migrations
python manage.py migrate

# Step 5: Run the development server
python manage.py runserver

# Step 6: Open your browser and visit:
http://127.0.0.1:8000/



[Tour and Travel Website_ ppt.pdf](https://github.com/user-attachments/files/20263296/Tour.and.Travel.Website_.ppt.pdf)
