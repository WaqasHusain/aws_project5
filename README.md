Two-Tier Website Deployment on AWS using EC2, RDS and ALB

Overview of Project:

This project involves deploying a To-Do List web application using a two-tier architecture on AWS. The architecture is designed for scalability, security, and cost-effectiveness by leveraging EC2 instances for the application layer and Amazon RDS for the database layer, with an Application Load Balancer (ALB) to distribute traffic.

Application Layer: Two EC2 instances host the Node.js application, ensuring high availability.
Database Layer: Amazon RDS is used to manage a MySQL database, storing application data securely.
Load Balancing & Routing: An Application Load Balancer (ALB) distributes incoming requests across both EC2 instances for fault tolerance.
Security & Networking: Security Groups, IAM roles, and VPC configurations are implemented for secure communication between components.

Services Used 🛠 :

1- Amazon EC2: Hosts the web application on two instances for redundancy and performance. [Compute]
2- Amazon RDS: Provides a managed relational database (MySQL) for application data. [Database]
3- Application Load Balancer (ALB): Distributes traffic across EC2 instances for scalability and reliability. [Networking]
4- Amazon VPC: Ensures secure networking with separate subnets for EC2 and RDS. [Networking]
5- IAM Roles and Policies: Grants necessary permissions for secure interactions between services. [Security]
6- Security Groups: Controls traffic flow between ALB, EC2, and RDS to enforce security. [Security]

Estimated Time & Cost:
This project is estimated to take about 2-3 hours
Cost: Free Tier Eligible (ALB costs according to the usage time)

Steps to be performed:

1- Pre-requisites
2- Setup VPC and Networking
3- Database Layer - Setup RDS 
4- Application Layer - Setup EC2 and Load balancer
