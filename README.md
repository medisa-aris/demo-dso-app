[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=com.example%3AdsoApp&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=com.example%3AdsoApp)

# demo-dso-app

## Overview

`demo-dso-app` is a demonstration project designed to practice **DevSecOps** methodologies using **Java technology**. This repository serves as a sandbox for exploring secure software development lifecycle (SDLC) practices, continuous integration/continuous delivery (CI/CD), automated security scanning, and containerization in a Java-based application environment.

## Purpose

The primary goal of this repository is to:

- Apply DevSecOps principles in real-world Java application scenarios
- Experiment with security integration in development pipelines
- Practice automated testing, vulnerability scanning, and secure deployment
- Understand best practices in managing Java application security across the SDLC

## Technologies Used

- Java (Spring Boot / Jakarta EE, depending on your stack)
- Maven or Gradle for build automation
- GitHub Actions / GitLab CI / Jenkins for CI/CD pipelines
- SonarQube, OWASP Dependency-Check, or Snyk for static code analysis and vulnerability scanning
- Docker for containerization
- Kubernetes (optional) for orchestration
- Trivy or Clair for container image scanning

## Getting Started

To run the project locally:

```bash
git clone https://github.com/your-org/demo-dso-app.git
cd demo-dso-app
./mvnw spring-boot:run   # or use Gradle if configured
