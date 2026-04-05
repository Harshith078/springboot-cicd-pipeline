# Spring Boot CI/CD Pipeline

This project demonstrates a complete CI/CD pipeline using:

- Jenkins
- SonarQube
- Nexus Repository
- Docker
- AWS EC2

## Pipeline Flow

1. Push code to GitHub
2. Jenkins triggers pipeline
3. Maven builds project
4. SonarQube analyzes code
5. Artifact stored in Nexus

## Run Locally

```bash
mvn spring-boot:run
