
# GarageIQ

GarageIQ is an intelligent garage management system designed to help manage garage operations and vehicle servicing.

## Core Features

- Customer management
- Vehicle records and service history
- Repair job tracking and worker assignments
- Spare-parts inventory management
- RAG-based AI assistant for answering questions using relevant garage records and documentation

## Technology Stack

- Frontend: HTML, CSS, Bootstrap
- Backend: Python and Flask
- Database: MySQL
- ORM: Flask-SQLAlchemy
- Authentication: Flask-Login (planned/integration pending)
- Visualizations: Chart.js
- AI: Retrieval-Augmented Generation (RAG)

## Project Setup

1. Install Python and MySQL.
2. Create a MySQL database named `garageiq`.
3. Create and activate a Python virtual environment.
4. Install dependencies:

   ```powershell
   python -m pip install -r requirements.txt
   ```

5. Create a `.env` file in the project root and configure your database connection:

   ```text
   DB_HOST=localhost
   DB_PORT=3306
   DB_NAME=garageiq
   DB_USER=your_mysql_username
   DB_PASSWORD=your_mysql_password
   ```

6. Start the application:

   ```powershell
   python run.py
   ```

7. Open `http://127.0.0.1:5000` in your browser.

## Security

- Never commit `.env` or database passwords to GitHub.
- Keep local virtual environments out of version control.
