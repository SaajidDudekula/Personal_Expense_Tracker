# Personal Expense Tracker (Python + Flask)

A simple Python-based web application to track daily expenses and view total and category-wise spending.  
This project focuses on clean backend logic, basic UI, and real-life usability.

---

## Features

- Add daily expenses with:
  - Amount
  - Category
  - Date
  - Optional description
- View all recorded expenses in a table
- Automatically calculate:
  - Total expenses
  - Category-wise totals
- Delete individual expense entries
- Persistent storage using SQLite

---

## Tech Stack

- **Backend:** Python, Flask  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, JavaScript  

---

## Project Structure

personal-expense-tracker-python/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│ └── index.html
│
└── static/
├── styles.css
└── app.js

yaml
Copy code

---

## Setup Instructions (Local)

1. Clone the repository:
```bash
git clone https://github.com/SaajidDudekula/personal-expense-tracker-python.git
cd personal-expense-tracker-python
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python app.py
Open your browser and visit:

cpp
Copy code
http://127.0.0.1:5000
Use Case
This application helps users keep track of personal spending and understand where their money is going on a daily basis.
It is suitable for beginners learning Flask, SQLite, and basic full-stack development.

Future Improvements
User authentication

Monthly reports and charts

Export expenses to CSV

Mobile-friendly UI enhancements

Author
Saajidvali Dudekula
Frontend Developer | Learning Python
🌐 https://saajiddudekula.com
pgsql
Copy cod
