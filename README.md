# Creating a Jenkins CI/CD Pipeline


In this project, we're going to be using a Docker installation of Jenkins to build a top-to-bottom CI/CD DevOps Pipeline.


# Setup


Step 1: Installing Docker Desktop

Step 2: Install Jenkins using Docker Compose (https://github.com/vdespa/install-jenkins-docker)
 - Note: Need to cd to "install-jenkins-docker" folder.
    - Use "docker compose up -d" to start.
    - Use "docker compose down" to stop Jenkins.
    - Access portal at http://localhost:8080/
  

# Testing our first Freestyle Job
<img width="780" height="538" alt="image" src="https://github.com/user-attachments/assets/30653376-a0b3-4c32-82eb-46869e707aef" />

We're going to be creating a "Freestyle" job titled "Freestyle1".

<br/>

Step 1: Setup Build Steps

For example, select "Execute Shell" and create command.
<img width="693" height="460" alt="image" src="https://github.com/user-attachments/assets/028db756-0d8d-4adf-a734-b382378b4596" />

Saving the job, starting job with "Build Now" command.
<img width="675" height="707" alt="image" src="https://github.com/user-attachments/assets/22c0ec26-2e26-4030-84eb-27970686a269" />

Then we can see the results by opening the "Console Output".
<img width="531" height="267" alt="image" src="https://github.com/user-attachments/assets/452ccdbb-f061-4d31-acf2-36c6f430bf7d" />


# Testing our first Pipeline Job

Using example "Hello World" Pipeline script.
<img width="1639" height="700" alt="image" src="https://github.com/user-attachments/assets/ce83785e-d38a-4b92-a739-0a915cc77911" />

Building and Confirming results in Console Output. Nearly the same as during the Freestyle Job example.
<img width="639" height="452" alt="image" src="https://github.com/user-attachments/assets/1fc73a83-cb20-486e-a439-32e904d100ae" />

# Building our first CI project

Note: I am using a forked Jenkins project created by Valentin Despa to build off of.
