# 🏥 GVP Care - Hospital Management System

A complete, professional Hospital Management System built with Python & Flask.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-2.x-green)
![SQLite](https://img.shields.io/badge/Database-SQLite-orange)

---

## ✨ Features

- 🏥 Beautiful Apollo-style Homepage
- 👤 Patient Register & Login
- 🩺 Doctor Register & Login
- 📅 Book & Manage Appointments
- ✅ Doctor Confirm/Cancel Appointments
- 📧 Email Notifications
- 📅 Appointments Calendar
- 🎁 Latest Health Offers
- 🛡️ Admin Panel
- 🔍 Admin Search
- 📊 Charts & Statistics
- 💾 Export Data to Excel
- 🔒 Change Password
- 📝 Patient Medical History
- ⭐ Patient Feedback & Ratings
- 👥 Patient Profile Page
- 📱 Mobile Friendly
- 🎨 Professional UI with Animations

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/hospital_db.git
cd hospital_db
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
python app.py
```

### 4. Open in browser
```
http://127.0.0.1:5000
```

---

## 👥 User Roles

| Role | Access |
|---|---|
| 🧑 Patient | Register, Login, Book Appointments, Medical History, Feedback |
| 🩺 Doctor | Login, Manage Appointments, Available Dates, View Feedback |
| 🛡️ Admin | Full Control, Charts, Export, Search, Manage All |

---

## 🗄️ Database Models

| Model | Description |
|---|---|
| Patient | Stores patient information |
| Doctor | Stores doctor information |
| Admin | Stores admin information |
| Appointment | Stores appointment records |
| MedicalHistory | Stores patient medical records |
| Feedback | Stores patient reviews and ratings |
| AvailableDate | Stores doctor available dates |
| Offer | Stores health offers |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Python | Backend language |
| Flask | Web framework |
| SQLite | Database |
| SQLAlchemy | ORM |
| Flask-Mail | Email notifications |
| openpyxl | Excel export |
| FullCalendar | Appointments calendar |
| Chart.js | Charts and statistics |
| HTML/CSS/JS | Frontend |

---

## 📁 Project Structure
```
hospital_db/
│
├── app.py                        ← Main Flask app
├── requirements.txt              ← Dependencies
├── README.md                     ← This file
├── .gitignore                    ← Git ignore
│
├── templates/
│   ├── index.html                ← Homepage
│   ├── login.html                ← Login page
│   ├── admin_login.html          ← Admin login
│   ├── admin_dashboard.html      ← Admin panel
│   ├── admin_search.html         ← Admin search
│   ├── patient_dashboard.html    ← Patient dashboard
│   ├── patient_profile.html      ← Patient profile
│   ├── patient_feedback.html     ← Patient feedback
│   ├── doctor_dashboard.html     ← Doctor dashboard
│   ├── doctor_feedbacks.html     ← Doctor reviews
│   ├── doctors.html              ← Doctors list
│   ├── medical_history.html      ← Medical history
│   └── change_password.html      ← Change password
│
└── static/
    └── style.css                 ← All styles
```

---

## 📝 Requirements
```
flask
flask-sqlalchemy
flask-mail
werkzeug
openpyxl
```

---

## ⚙️ .gitignore
```
# Database
hospital.db

# Python
__pycache__/
*.pyc
*.pyo
*.pyd
.env
venv/
env/

# VS Code
.vscode/

# Windows
Thumbs.db
desktop.ini
```

---

## 🚀 GitHub Commands
```bash
git init
git add .
git commit -m "🏥 GVP Care - Complete Hospital Management System"
git remote add origin https://github.com/yourusername/hospital_db.git
git push -u origin main
```

---

## 👨‍💻 Developer

Built with ❤️ by **OUR TEAM**

> GVP Care - Your Health, Our Priority 🏥
