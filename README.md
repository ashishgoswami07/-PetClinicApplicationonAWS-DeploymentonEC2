Spring PetClinic on AWS EC2 (Sandbox)
Overview

Deployed the Spring PetClinic Spring Boot application on an AWS EC2 instance using AWS Sandbox (Learner Lab).
The application is accessible through a public IP on port 8080.

Tech Stack

Java 17

Spring Boot (PetClinic)

Maven

AWS EC2

Amazon Linux 2023

H2 Database

Architecture
Browser → Public IP :8080 → EC2 → Spring Boot App → H2 DB

Key Steps

Launched EC2 (t2.micro, Amazon Linux 2023)

Opened ports 22 and 8080 in Security Group

Installed Java, Maven, Git

Cloned Spring PetClinic project

Configured app to bind to 0.0.0.0

Ran app using Maven

Accessed app via browser

Run Commands
git clone https://github.com/spring-projects/spring-petclinic.git
cd spring-petclinic
mvn spring-boot:run

Access Application
http://<EC2_PUBLIC_IP>:8080

Result

Successfully hosted a Spring Boot application on AWS EC2 and verified public access.

Resume Line

Deployed Spring PetClinic application on AWS EC2 (Sandbox) and exposed it using security group configuration.
