# AWS Jenkins Docker CI/CD Pipeline

## Project Overview
This project demonstrates an end-to-end CI/CD pipeline using AWS EC2, Jenkins, Docker, GitHub, and Nginx.

The pipeline automatically pulls source code from GitHub, builds a Docker image, deploys a container, and serves the application through Nginx.

## Technologies Used
- AWS EC2
- Jenkins
- Docker
- GitHub
- Nginx
- Linux (Ubuntu)

## Pipeline Workflow
1. Developer pushes code to GitHub
2. Jenkins pulls the latest source code
3. Docker image is built automatically
4. Docker container is deployed
5. Application becomes available through the web server

## Project Structure
├── Dockerfile
├── Jenkinsfile
├── index.html
├── style.css
└── README.md

## Screenshots
- Jenkins Dashboard
- Successful Build
- Running Docker Container
- Application Output

## Outcome
Successfully implemented an automated CI/CD pipeline that reduces manual deployment effort and demonstrates DevOps best practices.
