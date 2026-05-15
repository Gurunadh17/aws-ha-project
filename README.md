\# AWS Highly Available Web Application Project



\## Project Overview



This project demonstrates a secure and scalable AWS architecture using:



\- VPC

\- Public and Private Subnets

\- Bastion Host

\- Auto Scaling Group

\- Application Load Balancer

\- Private EC2 Instances



\## Architecture Flow



User → Application Load Balancer → Auto Scaling EC2 Instances



Bastion Host is used for secure SSH access to private instances.



\## Steps Performed



1\. Created VPC

2\. Created Public and Private Subnets

3\. Attached Internet Gateway

4\. Configured Route Tables

5\. Created Auto Scaling Group

6\. Auto Scaling launched Private EC2 Instances

7\. Created Bastion Host

8\. Connected Bastion to Private EC2

9\. Created Login Page

10\. Started Python HTTP Server on Port 8000

11\. Created Target Group

12\. Created Application Load Balancer

13\. Attached ALB to Target Group

14\. Accessed Application using ALB DNS



\## Technologies Used



\- AWS EC2

\- AWS VPC

\- Auto Scaling

\- Application Load Balancer

\- Linux

\- Python

\- HTML

\- SSH



\## Commands Used



```bash

python3 -m http.server 8000

ssh -i mykey.pem ec2-user@private-ip

```



\## Features



\- High Availability

\- Scalability

\- Secure Infrastructure

\- Load Balancing

\- Private Networking

