Spring PetClinic Deployment on AWS EC2
1. Project Overview

Deployment of the Spring PetClinic Spring Boot application on an AWS EC2 instance using AWS Sandbox.

2. Platform

AWS EC2 (Sandbox / Learner Lab)

Amazon Linux 2023

3. Technology Stack

Java 17

Spring Boot (PetClinic)

Maven

H2 Database

4. Deployment Steps (Summary)

Launched EC2 instance (t2.micro)

Configured Security Group (Ports 22, 8080)

Installed Java, Maven, Git

Cloned PetClinic repository

Ran Spring Boot application using Maven

5. Run Command
mvn spring-boot:run

6. Application Access
http://<EC2_PUBLIC_IP>:8080

7. Result

Spring PetClinic application successfully deployed and accessed publicly on AWS EC2.
