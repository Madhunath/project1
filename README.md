a # Spring Boot Shopping Cart Web Ap

## About

This is a demo project for practicing Spring + Thymeleaf. The idea was to build some basic shopping cart web app.

It was made using **Spring Boot**, **Spring Security**, **Thymeleaf**, **Spring Data JPA**, **Spring Data REST and Docker**. 
Database is in memory **H2**.

## Getting Into The Project

Created a Devops project using GitHub as SCM, Maven as a build Tool, Sonarqube as a code quality test tool, Jenkins as a CI/CD Tool, Docker as a containerization Tool, Docker Hub for container registry build, Ansible as a configuration management tool, Terraform as a infrastructure provision Tool and using AWS as a cloud platform to deploy a Java Web Application.

 1. Created AWS infrastructure using Terraform.
 2. Used ansible playbooks for installing Git, Docker, Jenkins, Sonarqube on sever(instance).
 3. Used GitHub for storing source code, Terraform file, Ansible playbook, Docker file and Jenkinsfiles.
 4. Maven is used as Build tool for Java source code.
 5. Sonarqube is used here to test the code quality.
 6. Used Dockerfile to build the image from the source code and stored that image on DockerHub.
 7. From that docker image, created a container to run the application.
 8. Used separate pipeline scripts to automate the entire process on jenkins.
