# Codeclause_Mail_Application

A secure mail application with user authentication, SMTP configuration, and email tracking.

## Features

1. User Authentication
  - Secure login and registration
  - Password hashing
  - Session management

2. SMTP Configuration
  - Store multiple SMTP configurations
  - Test SMTP connections
  - Secure credential storage

3. Email Management
  - Compose and send emails
  - Track sent emails
  - View email history
  - File attachments support

4. Database Integration
  - SQLite database for data persistence
  - Store user data, SMTP configs, and email records

## Technology Stack

- Backend: Python, Flask
- Database: SQLite
- Authentication: Flask-Login

## Installation

1. **Clone the repository:**
  ```sh
  git clone https://github.com/your-username/flask-mail-application.git
  ```

  ```sh
  cd flask-mail-application
  ```
2. **Create virtual environment:**
   ```sh
   python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
   
4. **Set up environment variables:**
   ```sh
   export FLASK_APP=run.py
   export FLASK_ENV=development
   ```

5. **Initialize database:**
   ```sh
   flask db init
   flask db migrate
   flask db upgrade
   ```

6. **Run the application:**
   ```sh
   flask run
   ```

## Usage
  1. Register a new account
  2. Configure SMTP settings
  3. Start sending emails
  4. Track email history in dashboard
