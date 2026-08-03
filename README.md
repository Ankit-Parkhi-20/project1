# 🚀 DevOps Project 1 - CI/CD Pipeline with Jenkins, Docker & GitHub

## Project Overview

This project demonstrates a simple CI/CD pipeline using GitHub, Jenkins,
and Docker. A static website is containerized with Docker and
automatically deployed whenever changes are pushed to the GitHub
repository.

## Technologies Used

-   Ubuntu Server 24.04 LTS
-   Jenkins
-   Docker
-   Git & GitHub
-   Apache2
-   GitHub Webhooks

## Workflow

1.  Create and test the website on the development server.
2.  Push the project to GitHub.
3.  Configure Jenkins with the GitHub repository.
4.  Add a GitHub webhook to trigger Jenkins automatically.
5.  Jenkins builds a Docker image.
6.  Jenkins deploys a new Docker container.
7.  Access the updated website from the browser.

## Docker Build Commands

``` bash
sudo docker rm -f container1 || true
sudo docker build -t webserver-image .
sudo docker run -dit --name container1 -p 5000:80 webserver-image
```

## Features

-   Automated CI/CD pipeline
-   Docker containerization
-   Jenkins automation
-   GitHub webhook integration
-   Automatic deployment

## Author

**Ankit Parkhi**

GitHub: https://github.com/Ankit-Parkhi-20
