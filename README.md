# ACEest Fitness & Gym DevOps Project

This project demonstrates a complete CI/CD pipeline using:

Flask
GitHub
Docker
GitHub Actions
Jenkins

## Run Locally

pip install -r requirements.txt
python app.py

## Run Tests

pytest

## Docker

docker build -t gym-app .
docker run -p 5000:5000 gym-app

## CI/CD

GitHub Actions automatically runs tests and builds Docker image on every push.

Jenkins pulls the project from GitHub and performs build verification.