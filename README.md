# 🚀 Jenkins CI/CD Demo Website

This repository contains a simple static HTML webpage used to demonstrate a basic CI/CD pipeline using Jenkins. The goal is to automate the build and deployment process of a web application using Docker and Jenkins.

## 📄 Project Overview

- **Tech Stack**: HTML, Docker, Jenkins
- **Purpose**: Showcase how Jenkins can be used to automate deployment of a static website.
- **Deployment Target**: Localhost via Docker (Nginx)

## 🧰 Files Included

- `index.html`: The main webpage.
- `Dockerfile`: Used to containerize the HTML page with Nginx.
- `Jenkinsfile`: Defines the CI/CD pipeline stages.

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
 
 2. Build the Docker image:

  docker build -t static-html-site .

3. Run the container:

docker run -d -p 8080:80 static-html-site

4. Open your browser and visit:
http://localhost:8080
