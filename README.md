Devops Project: Automated CI/CD Pipeline for Web Application using GitHub, Jenkins, Maven, Ansible, Docker, and Kubernetes on AWS

1.Introduction
Tools
Git - Local version control system
GitHub - Distributed version control system
Jenkins - Continuous integration tool.
Maven - Build tool
Ansible - Configuration management and deployment tool
Docker - Containerisation
Kubernetes - Container management tool
Setup all these environments on AWS

Devops Workflow
Source code is with the developer.During the development phase developers commit there code to github.
We need to build the code. For building the code we use continuous integration tool called Jenkins. Once jenkins build the code it generates artifacts. Those artifacts we need to deploy on the target environment.
We will use ansible as a deployment tool. Ansible can deploy our application on target environments like VM, docker or kubernetes.
We will deploy the application first on VM, then on Docker and last on Kubernetes.

![Screenshot 2025-01-02 092620](https://github.com/user-attachments/assets/b738830e-a0d1-4f6f-9220-13d898e20861)
![Screenshot 2025-01-02 092620](https://github.com/user-attachments/assets/5162632c-f9ac-4e77-a9e1-f0ab347951c6)



