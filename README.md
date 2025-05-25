# 📝 Dockerized Flask To-Do App

A simple and lightweight To-Do List web application built using **Flask** and **Python**, containerized with **Docker**. This project demonstrates how to build, containerize, and run a Python web app that’s ready for deployment on cloud platforms such as AWS.

---

## 🚀 Features

- ✅ Add, view, and delete tasks
- 🖥️ Simple and clean UI
- 🧪 Python Flask backend
- 📦 Containerized using Docker
- ☁️ Ready for cloud deployment (Render)

---

## 📁 Project Structure

flask-todo-docker/
│
├── app.py # Main Flask application
├── templates/
│ └── index.html # Frontend UI
├── static/
│ └── style.css # CSS styling
├── requirements.txt # Python dependencies
├── Dockerfile # Docker container config
└── README.md # Project documentation

----

## Tech Stack

| Layer        | Technology        |
|--------------|-------------------|
| Backend      | Python, Flask     |
| Frontend     | HTML, CSS         |
| Container    | Docker            |
| Version Ctrl | Git + GitHub      |

-----

## 🛠️ Getting Started
### 🔹  Run with Docker 

#### ✅ Prerequisites
- Docker installed on your system

#### 📦 Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/flask-todo-docker.git
   cd flask-todo-docker

2. **Build the Docker Image**
     ```bash
     docker build -t flask-todo-app .

3. **Run the Docker Container**
   ```bash
   docker run -p 5000:5000 flask-todo-app

4. **Visit the app in browser**
   Open your browser and go to: http://localhost:5000 



