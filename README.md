Deploy Netflix Clone on Cloud using Jenkins - DevSecOps Project!

Install Docker in the EC2 server:
sudo apt-get update
sudo apt-get install docker.io -y
sudo usermod -aG docker $USER  # Replace with your system's username, e.g., 'ubuntu'
newgrp docker
sudo chmod 777 /var/run/docker.sock

Build and run your application using Docker containers:
docker build -t netflix .
docker run -d --name netflix -p 8081:80 netflix:latest

Install SonarQube and Trivy on the EC2 instance to scan for vulnerabilities.

Integrate SonarQube with your CI/CD pipeline.
Configure SonarQube to analyze code for quality and security issues.

Install Necessary Plugins in Jenkins
 Eclipse Temurin Installer (Install without restart)
 SonarQube Scanner (Install without restart)
 NodeJs Plugin (Install Without restart)
 Email Extension Plugin

Configure CI/CD Pipeline in Jenkins

Install Docker Tools and Docker Plugins

Install Prometheus and Grafana

Create Kubernetes Cluster with Node groups for orchestration
