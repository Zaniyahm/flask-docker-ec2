# Flask App Dockerized & Deployed on AWS EC2 ☁️🐳

This project is a beginner-friendly example of deploying a Flask app using Docker on an AWS EC2 instance.

## 🔧 Project Structure

- `app.py` – Simple Flask app with one route
- `Dockerfile` – Container setup
- `requirements.txt` – Python dependencies

## 🐳 Run Locally with Docker

```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app
