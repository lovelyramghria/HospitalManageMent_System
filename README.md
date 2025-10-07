 
🏥 Hospital Management System

The **Hospital Management System** is a full-stack web application built with **Django** and **SQL database**.  
The main goal of this project is to digitalize and simplify hospital operations — from **patient registration** to **doctor management**, **appointments**, and **record keeping** — all in one platform.

---

## 📖 About the Project

This system automates the hospital management process and provides dedicated panels for **Patients**, **Doctors**, and **Admins**.  
All data — including patient details, doctor records, and appointments — is securely stored in an **SQL database (MySQL)**.

---

## ✨ Key Features

### 👤 Patient Features
- Patients can **register** and **log in**.
- Patients get their own **dashboard**.
- They can view **available doctors** and their details.
- Choose from various **services**, including:
  - 🧪 Medical Tests  
  - 🩺 General Checkup  
  - ❤️ Cardiology  
- Patients can be **admitted** and **discharged** directly from the system.

---

### 👨‍⚕️ Doctor Features
- Doctors can **log in** to their own panel.
- They can view and manage **patient details**.
- Access appointment and medical record data.
- Manage their schedules and patient information easily.

---

### 🛠️ Admin Features
- The **Admin Dashboard** allows full control of the system.
- Admin can manage **patient records** and **doctor details**.
- Admin can monitor all operations from a single dashboard.
- Full control over the hospital’s data and workflows.

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** SQL (SQLite / MySQL) – used to store patient, doctor, and appointment data  
- **Other Tools:** Django ORM, Django Admin Panel

---

## 🚀 How to Run the Project Locally

Follow these steps to run the project on your local machine 👇

 1. Clone the Repository
 
git clone https://github.com/lovelyramghria/HospitalManageMent_System.git
cd HospitalManageMent_System

2. Create a Virtual Environment (Optional but Recommended)
python -m venv venv
# Activate it:
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

5. Run Database Migrations
python manage.py migrate

7. Start the Development Server
python manage.py runserver
Now open your browser and visit:
👉 http://127.0.0.1:8000/


📸 Core Functionalities

✅ Patient registration and login
✅ Doctor login panel
✅ Admin dashboard with full control
✅ Manage patients and doctors
✅ View and book services (Medical Tests, General Checkup, Cardiology)
✅ Admit and discharge patients
✅ Secure SQL database integration

📬 Contact

👨‍💻 Developer: Lovely Ramghria
📧 Email: [lovelyramghria39@gamil.com]
