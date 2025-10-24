# Internship Projects: OnlineQuiz & Job Board

This repository contains two full-stack web applications I developed during my internship using **Flask**, **HTML**, **CSS**, **JavaScript**, and **SQLite**.  
Both projects were built to strengthen my understanding of backend logic, database management, and front-end integration.

---

## 🚀 Projects Overview

### 🧠 1. OnlineQuiz
**Description:**  
A web-based quiz application where users can register, take quizzes, and view their scores.  
Admins can add quiz questions.

**Key Features:**
- User registration and login using Flask sessions    
- Real-time score calculation and feedback  
- SQLite database integration for questions and results  
- Responsive front-end using HTML, CSS, and JavaScript

**Tech Stack:**
- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite  
- **Other Tools:** Flask-WTF, Jinja2 Templates

---

### 💼 2. Job Board
**Description:**  
A job portal that allows employers to post job listings and job seekers to apply.  
Includes authentication, job filtering functionalities.

**Key Features:**
- User roles: Employer and Job Seeker  
- Job posting, editing, and deletion by employers  
- Job search   
- Application submission 
- SQLite database for job listings and users  
- Clean UI built with HTML, CSS, and JS

**Tech Stack:**
- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite  
- **Other Tools:** Flask-Login, WTForms

---

## 🧰 Setup Instructions

Follow these steps to run the projects locally.

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```
### Navigate to a project folder
cd OnlineQuiz
# or
cd Job Board

### Create and activate a virtual environment
python -m venv venv
source venv/bin/activate     # On macOS/Linux
venv\Scripts\activate        # On Windows


### Install dependencies
pip install -r requirements.txt

### Run the Flask application
python app.py

### Open in browser
