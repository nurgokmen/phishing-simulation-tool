# Flask Phishing Simulation Tool

This project is a simple Flask-based web application that collects form data (e.g., username and password) submitted by users. It serves as a foundational tool for understanding how phishing simulations work and for testing the security awareness of users.

# Features

**Home Page**: A basic HTML form where users can enter a username and password.
**Data Handling**: Captures and displays the submitted form data for simulation purposes.
**Lightweight and Extensible**: Easily customizable for additional features or use cases.

# Prerequisites

Before running this project, ensure you have the following installed:

- Python 3.x
- Flask library (pip install flask)
- 
# Installation

**Clone this repository:
```
git clone https://github.com/yourusername/phishing-simulation-tool.git
```

Navigate to the project directory:

bash
Copy code
cd phishing-simulation-tool  
Create and activate a virtual environment (optional but recommended):

```
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies:
```
pip install flask
```
# Running the Application

Start the Flask development server:
```
python app.py
```

Open your browser and navigate to:
```
http://127.0.0.1:5000/
```

# File Structure
```
phishing-simulation-tool/  
├── templates/  
│   └── index.html  # HTML form for user input  
├── app.py          # Main Flask application  
└── README.md       # Project documentation
```
# How It Works
The home page displays a form (index.html) where users can enter their username and password.
When the form is submitted, the data is sent to the /submit route using the POST method.
The Flask app captures and processes the data, then displays it back to the user.

# Disclaimer
This project is for practical purposes only. It is intended to demonstrate how phishing simulations work to improve awareness and security practices. Do not use this application for malicious purposes or to harm others.

