CI/CD Pipeline using Jenkins, Docker, Kubernetes & AWS

Project Overview:
This project demonstrates an end-to-end DevOps CI/CD pipeline where application code is automatically built, tested, containerized, and deployed using Jenkins, Docker, Kubernetes, and AWS EC2.

Tools & Technologies Used:
- Git & GitHub
- Jenkins
- Maven
- Docker
- Kubernetes (Minikube)
- AWS EC2
- Linux (CentOS)

Project Architecture:
1. Developer pushes code to GitHub
2. Jenkins triggers CI/CD pipeline
3. Maven builds the application
4. Docker creates container image
5. Kubernetes deploys containers
6. Application runs on AWS EC2

Project Structure:
devops-project/
* Dockerfile
* Jenkinsfile
* deployment.yaml
* pom.xml
* README.md
* src/
