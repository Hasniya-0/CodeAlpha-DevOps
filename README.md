# CodeAlpha - Docker Web Server 🐳

## 📌 Project Overview
This project is part of the **CodeAlpha DevOps Internship Task 4**.  
It demonstrates how to deploy a simple web server using **Docker containers**.

The main goal is to learn:
- Docker image creation
- Container deployment
- Running a web server inside Docker
- Port mapping and container management

---

## 🛠️ Technologies Used
- Docker
- Nginx (Web Server)
- HTML
- PowerShell / CLI

---

## 📁 Project Structure
CodeAlpha-DockerWebServer/
│── Dockerfile
│── index.html
│── README.md

---

## ⚙️ How It Works
1. A simple HTML page is created (`index.html`)
2. A Dockerfile is used to build a custom Nginx image
3. Docker builds the image
4. A container is created and runs the web server
5. The website is accessible via browser

---

## 🚀 Docker Commands Used

### Build Image
```bash
docker build -t codealpha-webserver .


Run Container
        docker run -d -p 8080:80 codealpha-webserver

Check Running Containers
         docker ps


Stop Container 
         docker stop <container_id>

Access The Web Server 
        http://localhost:8080



Key Learnings
Docker basics and containerization
Creating Docker images using Dockerfile
Running and managing containers
Web server deployment using Nginx


Author :M.A.S. Hasniya Banu
STUDENT ID :CA/DF1/32062
CodeAlpha DevOps Intern