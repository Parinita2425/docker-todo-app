# Dockerized To-Do List Application

## Project Description
This is a simple To-Do List web application developed using Python Flask, HTML, and CSS. The application is containerized using Docker to make deployment easier and more consistent.

## Features
- Add new tasks
- View tasks
- Delete tasks
- Simple and user-friendly interface
- Runs inside a Docker container

## Technologies Used
- Python
- Flask
- HTML
- CSS
- Docker
- Linux (Ubuntu)
- Git
- GitHub

## Project Structure

```text
docker-todo-app/
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── app.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
└── README.md
```

## How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/Parinita2425/docker-todo-app.git
```

### Step 2: Open the project folder

```bash
cd docker-todo-app
```

### Step 3: Build the Docker image

```bash
docker build -t todo-app .
```

### Step 4: Run the Docker container

```bash
docker run -d -p 5000:5000 --name my-todo-container todo-app
```

### Step 5: Open the application

Open your browser and visit:

http://localhost:5000

## Stop the Container

```bash
docker stop my-todo-container
```

## Author

Parinita Ganesh Gurram

GitHub: https://github.com/Parinita2425