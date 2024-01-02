---
title: Achat (devops)
description: Devops project with goal of building a custom CI/CD pipline with jenkins and docker compose
pubDate: 24 May 2023
tags: ["SpringBoot","DevOps","Jenkins","Docker"]
---
# Achat (DevOps) Project

## Description:
The Achat (DevOps) project focuses on automating the development and deployment of the Achat store management application—a Spring Boot-based store management app. It involves building a customized CI/CD pipeline using Jenkins and Docker Compose for efficient and reliable processes.


### Key Features:

- Setup:
Vagrant is used to configure a virtual machine hosting Jenkins and Docker, providing a consistent environment for the CI/CD pipeline.

- CI/CD Pipeline:
Implemented in Groovy within Jenkins, the custom pipeline automates tasks, ensuring smooth development and deployment.


### Pipeline Steps:

1. Cloning & Compilation:
    - Fetches the latest code from GitHub, compiles using Maven, and runs comprehensive tests with Mockito.

1. Quality Check:
    - Integrates SonarQube for static code analysis, maintaining code quality.

1. Artifact Management:
    - Uses Nexus repository for storing and managing project artifacts.

1. Monitoring & Notification:
    - Integrates Prometheus for monitoring, Grafana for visualization, and configures email notifications for pipeline failures.

1. Dockerization & Deployment:
    - Dockerizes the application, creating a portable environment, and deploys it using Docker Compose with MySQL. Pushes the Docker image to DockerHub.

### Technologies Used:

+ Development:
    * Leverages the Spring Boot framework for Java-based enterprise applications.

+ DevOps:
    * Jenkins orchestrates the CI/CD pipeline, while Docker provides containerization for consistent deployment.

### Conclusion:
The Achat (DevOps) project showcases the efficiency gained through automating development and deployment. The custom CI/CD pipeline ensures continuous integration and deployment, fostering maintainability and scalability.

### links:
[Github](https://github.com/abdou6666/devops_project/tree/brahim)