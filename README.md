🧾 Overview

This project demonstrates how to implement a DevSecOps CI/CD pipeline using GitHub Actions.
It automates the process of building, testing, and deploying a simple Node.js web application that runs inside a Docker container.
Security scanning with npm audit is integrated into the workflow, ensuring that vulnerabilities are detected early during the development lifecycle.

⚙️ Features

Automated CI/CD pipeline using GitHub Actions

Security scanning using npm audit

Containerized Node.js app using Docker

Continuous integration on every push or pull request

Simple, lightweight, and reproducible setup

🧰 Tools & Technologies

Node.js & Express.js

Docker

GitHub Actions

npm (Node Package Manager)

Visual Studio Code

Git

🚀 How to Run the Project
# Clone the repository
git clone https://github.com/shreeyansh07/DevOps-Project.git
cd DevOps-Project

# Build the Docker image
docker build -t devopsproject .

# Run the container
docker run -d -p 8080:3000 devopsproject


Open your browser and go to http://localhost:8080

You should see the message: “Hello from DevSecOps Sample App 🚀”

🔁 GitHub Actions Workflow

The GitHub Actions workflow file (.github/workflows/security-ci.yml) is automatically triggered on every push to the main branch.
It performs the following tasks:

Checks out the code

Installs dependencies

Runs a security scan using npm audit

Builds a Docker image

Runs and verifies the container

📸 Screenshots

Project structure in VS Code

Successful Docker image build and run logs

Browser showing the running app

GitHub Actions workflow success output

npm audit results

🧠 Conclusion

This project showcases how DevOps and security practices can be combined through automation using GitHub Actions.
By integrating security checks directly into the CI/CD pipeline, it ensures reliable, secure, and fast application delivery with minimal manual effort.

👨‍💻 Author

Name: Shreeyansh Saha
Course: B.Tech in Computer Science and Engineering
Institution: DIT University, Dehradun

📅 Project Summary

This mini project titled “DevSecOps CI/CD Pipeline using GitHub Actions” was independently designed and implemented by me as part of my academic coursework.
The work involves setting up a CI/CD pipeline for a containerized Node.js application with integrated security scanning using GitHub Actions.
All configurations, scripts, and implementation steps were developed, tested, and documented by me for academic purposes.