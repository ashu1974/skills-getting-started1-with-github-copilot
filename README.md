# Getting Started with GitHub Copilot

_Get started using GitHub Copilot in less than an hour._

## Welcome

This repository contains a simple FastAPI application for Mergington High School's extracurricular activities management system. It's designed to help you learn GitHub Copilot by building and enhancing this application.

## What's Included

- **FastAPI Application**: A simple REST API for managing school activities
- **Web Interface**: An HTML-based front end for viewing and signing up for activities
- **Learning Exercise**: Practice using GitHub Copilot to enhance and debug this application

## Getting Started

1. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:

   ```bash
   cd src
   python -m uvicorn app:app --reload
   ```

3. Open your browser and visit:
   - Web Interface: http://localhost:8000
   - API Documentation: http://localhost:8000/docs
   - Alternative API docs: http://localhost:8000/redoc

## Project Structure

```
.
├── README.md           # This file
├── requirements.txt    # Python dependencies
└── src/
    ├── app.py          # Main FastAPI application
    ├── README.md       # API documentation
    └── static/
        └── index.html  # Web interface
```

## Features

- View all available extracurricular activities
- Sign up for activities with your school email
- Track participant counts for each activity

## Learning with GitHub Copilot

Use GitHub Copilot to:
- Add new API endpoints
- Enhance the web interface
- Add input validation
- Implement new features
- Debug and fix issues

---

Get started using GitHub Copilot
