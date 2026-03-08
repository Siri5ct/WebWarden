# Web Warden – Student Outpass Management System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Framework-Flask-green)
![HTML](https://img.shields.io/badge/Frontend-HTML-orange)
![JSON](https://img.shields.io/badge/Data-JSON-yellow)

## 👨‍💻 Developed By Tean

---

# 📖 Project Overview

Web Warden is a simple web-based system designed to manage **student outpass requests** digitally.  
Instead of using manual registers or paperwork, students can submit requests online and wardens can review the status easily.

The system uses a **Flask backend**, **HTML templates**, and a **JSON file database** to store requests.

This project demonstrates how a basic **web application with request tracking** can be implemented using Python and Flask.

---

# 🎯 Objective

The goal of this project is to build a lightweight system that can:

- Allow students to submit outpass requests
- Store requests in a structured format
- Display request status
- Provide a simple interface for request tracking

This helps automate the **hostel outpass approval process**.

---

# 🏗 System Architecture

```
User Browser
     ↓
HTML Templates
     ↓
Flask Web Application (app.py)
     ↓
JSON Data Storage
     ↓
Display Request Status
```

---

# 🚀 Technologies Used

| Technology | Purpose |
|-----------|---------|
| Python | Backend programming |
| Flask | Web application framework |
| HTML | Frontend templates |
| JSON | Data storage for requests |
| GitHub | Version control and repository hosting |

---

# 📁 Project Structure

```
Web_Warden
│
├── app.py
├── outpass_requests.json
│
├── templates
│   ├── index.html
│   └── status.html
│
└── README.md
```

---

# ⚙️ How the System Works

### 1️⃣ Submit Outpass Request

Students enter their details in the **main page form**.

Example details:

- Student Name
- Roll Number
- Reason for Outpass
- Date

The data is submitted to the Flask backend.

---

### 2️⃣ Data Storage

The request is stored inside the JSON file:

```
outpass_requests.json
```

Example structure:

```json
[
  {
    "name": "John Doe",
    "roll_number": "12345",
    "reason": "Medical visit",
    "status": "Pending"
  }
]
```

---

### 3️⃣ Request Status Page

Students can check their request status on the **status page**.

File:

```
templates/status.html
```

The system reads the stored JSON data and displays the request status.

---

# ▶ Running the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/web-warden.git
cd web-warden
```

---

### 2️⃣ Install Flask

```bash
pip install flask
```

---

### 3️⃣ Run the Application

```bash
python app.py
```

---

### 4️⃣ Open in Browser

Visit:

```
http://127.0.0.1:5000
```

You will see the **Outpass Request Form**.

---

# 📄 Templates Used

### index.html

Main page containing the **outpass request form**.

Features:

- Input fields for student details
- Form submission to backend
- Simple user interface

---

### status.html

Displays the **status of submitted requests**.

Features:

- Reads request data
- Displays approval status
- Shows pending or approved requests

---

# 📊 Current Status

| Feature | Status |
|-------|-------|
| Request Form | ✅ Completed |
| JSON Data Storage | ✅ Completed |
| Status Page | ✅ Completed |
| Web Interface | ✅ Completed |

---

# 🔮 Future Improvements

Possible enhancements for the system:

- Admin login for wardens
- Request approval or rejection system
- Database integration (SQLite / MySQL)
- Email notifications
- Improved UI using CSS / Bootstrap

---

# ✅ Final Outcome

Web Warden provides a simple **digital solution for hostel outpass management**.

The system allows:

- Students to submit requests online
- Requests to be stored automatically
- Easy status checking

This project demonstrates the basics of building a **Flask-based web application with persistent data storage**.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
