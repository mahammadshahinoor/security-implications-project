# 🔐 Security Implications Web Application

## 🌐 Live Demo

http://13.205.61.55

---

## 📌 Description

This is a Flask-based web application designed to demonstrate the **security implications of direct user file uploads to cloud storage**.
The system implements encryption, role-based access control, and logging to ensure secure handling of sensitive data.

---

## 🚀 Features

* 🔑 Admin and User Authentication
* 👤 User Registration with validation
* 🔒 Secure File Upload with Encryption (Fernet AES)
* 📊 Performance Reports and Activity Logs
* 📁 File Listing and Search Functionality
* 🔐 Decryption Key Download System
* 📈 Graph-based Results Visualization

---

## 🛠️ Tech Stack

* Python (Flask)
* SQLite Database
* HTML, CSS, JavaScript
* AWS EC2 (Cloud Deployment)
* Nginx (Reverse Proxy)
* Git & GitHub (Version Control)

---

## ☁️ Deployment on AWS EC2

This project is deployed on Amazon Web Services using an Ubuntu EC2 instance.

### Steps:

1. Launch EC2 instance and configure security groups
2. Connect using SSH (Git Bash)
3. Upload project using SCP
4. Install dependencies and setup virtual environment
5. Run Flask application
6. Configure Nginx as reverse proxy
7. Setup systemd service for auto-start
8. Assign Elastic IP for static access

---

## 🧠 Architecture

User → Nginx → Flask Application → SQLite Database

---

## ▶️ Run Locally

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open:
http://127.0.0.1:5000

---

## 🔒 Production Setup

* Gunicorn as WSGI server
* Nginx as reverse proxy
* Systemd service for auto start
* Elastic IP for static deployment

---

## 📂 Project Structure

```
security_app/
│── app.py
│── requirements.txt
│── templates/
│── static/
│── database/
```

---

## 💼 Resume Highlight

Deployed a Flask-based secure file management system on AWS EC2 with encryption, role-based access control, and Nginx reverse proxy.

---

## 📧 Author

Mahammad Shahinoor
