# Dockerized Flask App on AWS EC2

## 📌 Description
This project demonstrates how to Dockerize a simple Flask application and deploy it on an AWS EC2 instance using Docker.

---

## 🚀 How to Run Locally

```bash
# Build the Docker image
docker build -t flask-app .

# Run the container
docker run -p 5000:5000 flask-app
