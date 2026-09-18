# CRM Software: Customer & Lead Management System

A beginner-friendly full-stack CRM built with Flask, SQLite, HTML, CSS and JavaScript.

## Features
- Signup, login and logout
- Customer CRUD
- Lead CRUD
- Lead filtering by status and assigned user
- Interaction logging for calls, emails and notes
- Dashboard statistics and sales pipeline
- CSV customer export
- Responsive UI
- SQLite database created automatically

## Run locally

### Windows
1. Install Python 3.11+ from https://www.python.org/downloads/
2. Open Command Prompt in the `backend` folder.
3. Create a virtual environment:
   `python -m venv venv`
4. Activate it:
   `venv\Scripts\activate`
5. Install dependencies:
   `pip install -r requirements.txt`
6. Start the application:
   `python app.py`
7. Open http://127.0.0.1:5000 in your browser.

The SQLite database `crm.db` is created automatically after the first run.

## Suggested demo
Create an account, add 3 customers, create 4-6 leads with different statuses, assign them to users, log 3 interactions, then show the dashboard and CSV export.

## Project structure
CRMProject/
  backend/
    app.py
    requirements.txt
  frontend/
    index.html
    style.css
    app.js
  README.md
  .gitignore
