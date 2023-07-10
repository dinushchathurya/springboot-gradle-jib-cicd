### CICD Pipeline for Dockerize Java Springboot Gradle Application using Job and push Docker image to DockerHub 

This is a sample project to demonstrate the CI/CD pipeline for a Java Springboot Gradle Application build uisng Jib and push Docker image to DockerHub. The pipeline is built using GitHub Workflow. The pipeline is triggered when a commit is made to the GitHub repository. The pipeline consists of the following stages:

1. Checkout the code from GitHub repository
2. Setup Java JDK 11
3. Setup Gradle
4. Build the Java Springboot Gradle Application
5. Unit Test the Java Springboot Gradle Application
6. Build the Docker image using Jib
7. Push the Docker image to DockerHub

The pipeline is defined in the file [action.yml](.github/workflows/action.yaml)


