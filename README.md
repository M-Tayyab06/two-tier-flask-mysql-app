# Two-Tier Flask Application with Docker

This is a two-tier web application built with Flask and MySQL, containerized using Docker. The project demonstrates how to integrate a Flask backend with a MySQL database and deploy it seamlessly using Docker and Docker Compose.

---

## Features
- **Flask Backend**: A lightweight web server.
- **MySQL Database**: Persistent data storage for your application.
- **Dockerized Application**: Easy to set up and deploy with Docker.
- **Dynamic UI**: A modern web interface for interacting with the backend.

---

## Prerequisites
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/)

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/flask-docker-app.git
cd flask-docker-app



flask-docker-app/
│
├── app/
│   ├── templates/        # HTML templates for the Flask app
│   │   └── index.html    # Main UI file
│   ├── app.py            # Flask application code
│   ├── Dockerfile        # Dockerfile for the Flask app
│   └── requirements.txt  # Python dependencies
│
├── mysql-data/           # MySQL persistent storage
├── docker-compose.yml    # Docker Compose configuration
├── message.sql           # SQL file for database setup
└── README.md             # Project documentation
