# Skill Gap Identifier & Training Recommender using Python and AI

This project automates the process of identifying employee skill gaps and recommends personalized training programs from Coursera, using Python, NLP models, and email automation.

---

## 🚀 Project Overview

- Load employee skills and role requirements from CSV files
- Identify missing skills using semantic similarity (BERT model)
- Search Coursera API for appropriate training courses
- Recommend trainings and send personalized emails to each employee
- Model the business process using BPMN (Business Process Model and Notation)

---


---

## 🛠️ Initial Setup

1. **Install Python 3.8 or above**

   [Download Python](https://www.python.org/downloads/)

2. **Create and activate a virtual environment (optional but recommended)**

```bash
python -m venv env
source env/bin/activate    # Linux/Mac
env\Scripts\activate       # Windows


## Required libraries to install
pip install pandas requests sentence-transformers scikit-learn
pip install secure-smtplib


## Update the email credentials in the script
SENDER_EMAIL = 'youremail@gmail.com'
SENDER_PASSWORD = 'yourapppassword'   # Use Gmail App Passwords for security




## Update the working directory in the script if needed
working_dir = r'C:\Users\<YourName>\Downloads\IAPA\\'
