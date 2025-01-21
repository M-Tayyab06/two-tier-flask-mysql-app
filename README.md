# Two-Tier Flask Application with Docker

This project is a two-tier web application built with Flask and MySQL, designed to be deployed using Docker. It demonstrates a simple, dynamic user interface powered by Flask with a robust MySQL database backend, all orchestrated using Docker Compose.

---

## Features
- **Flask Web Application**: A lightweight, dynamic backend.
- **MySQL Database**: Persistent storage for application data.
- **Dockerized Architecture**: Simplifies setup and deployment.
- **Responsive UI**: Dark-themed modern web interface.

---

## Prerequisites
Before running this application, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/)

---

## Getting Started

### Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/flask-docker-app.git
cd flask-docker-app
```

### Build and Run the Application
1. **Build Docker Images**:
   ```bash
   docker-compose build
   ```

2. **Run the Application**:
   ```bash
   docker-compose up
   ```

3. **Access the Application**:
   Open your browser and visit:
   ```
   http://localhost:5000
   ```

---

## Project Structure

```
flask-docker-app/
│
├── app/
│   ├── templates/        # HTML templates for the Flask app
│   │   └── index.html    # Main UI file
│   ├── app.py            # Flask application logic
│   ├── Dockerfile        # Dockerfile for the Flask app
│   └── requirements.txt  # Python dependencies
│
├── mysql-data/           # MySQL persistent storage
├── docker-compose.yml    # Docker Compose configuration
├── message.sql           # SQL script for database setup
└── README.md             # Project documentation
```

---

## How to Push to GitHub

1. **Initialize Git**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Two-tier Flask app with Docker"
   ```

2. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com/) and create a new repository.

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/your-username/flask-docker-app.git
   git branch -M main
   git push -u origin main
   ```

---
