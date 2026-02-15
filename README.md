
# Flask Login & Session Management App

This is a simple Flask web application that demonstrates:

- User Login Form
- Session Handling
- Redirecting Between Pages
- Logout Functionality

Built using Python and Flask.

---

##  Features

- Login form using POST method
- Session storage using Flask session
- Redirect to welcome page after successful login
- Logout functionality
- Basic credential validation

---

## Technologies Used

- Python 3.x
- Flask
- HTML (embedded in Python)
- Session Management

---

##  Project Structure

Flask_Project/
│
├── app.py
├── requirements.txt
└── README.md

---

##  Login Credentials (For Testing)

Username: admin  
Password: 123  

---

##  How To Run The Project

1. Install Flask:
   pip install flask

2. Run the application:
   python app.py

3. Open browser and visit:
   http://127.0.0.1:5000/

---

##  Routes

| Route | Description |
|-------|------------|
| / | Login Page |
| /welcome | Welcome Page (Protected) |
| /logout | Logout and redirect to login |

---

##  Learning Concepts Demonstrated

- Flask Routing
- GET and POST methods
- Form handling
- Redirect and url_for()
- Session management
- Response object usage

---

##  Note

This is a basic learning project.  
For production applications:

- Passwords should be hashed
- Use database for storing users
- Use secure authentication system
- Enable HTTPS

---

