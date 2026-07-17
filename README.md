# AWS Three-Tier Job Portal
Three-Tier Job Portal deployment on AWS by using VPC,RDS, Auto Scaling Group, EC2, Load Balancer.
# PROJECT OVERVIEW
In this project I deployed a highly available job portal on AWS. I created custom VPC for networking according to my project requirements.Created an amazon RDS database in a private subnet to securely store application data so user can not access database directlyl. Created Target Group and Launch Template. Luanch template acts like a blueprint for launching new Instances and Target Group perform health check and route traffic to healtyh instances. I attach load balance to Auto Scalling Group so when users access our website then load balance can distribute the traffic across healthy instances  and if their more traffic comes to our website then according to load ASG can create new Instance. Through RDS endpoint connect a web application. Launch my job portal on AWS.

# AWS services used
Amazon EC2
Amazon VPC
Internet Gateway
Nat Gateway
Public and Private Subnet
Bastion Host
Route Table
Security Group
Target Group(tg)
Launch Template
Amazon RDS
Application Load Balancer(ALB)
Auto Scaling Group(ASG)

# PROJECT ARCHITECTURE
Created a Custom VPC.
Configured Public and Private Subnet.
Attached and Internet Gateway to VPC.
Used a NAT Gateway for Internet acces from private subnet.
Edit Route Table for public and private subnet.
Created a Bastion Host in public subnet for secure access.
Deployed the Web Application on EC2 Instance.
Created Launch template.
Created a target Group.
Configured an elastic Load Balancer for distribute incoming traffic.
Configured Auto Scaling Group for high availability.
Created an Amazon RDS MYSQL database in private subnet.
Connected application to RDS database using RDS endpoint.

# FEATURES
High Availabilty
Auto Scaling
Secure Network Architecture
Load Balancing
Private Database

# database
Service: Amazon RDS
Engine: MYSQL
## screenshots
## VPC
![VPC Screenshot](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175815.png)
## Public Subnet
![Public and Private Subnet Screenshot](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175857.png)
## RDS Database
![RDS Database](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175512.png)
## Target Group
![Target Group](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20180156.png)
## Launch Template
![Launch Template](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20180620.png)
## Auto Scaling Group
![Auto Scaling Group](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20180403.png)
## Load Balancer
![Load Balancer](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175303.png)
## Instances & Bastion Host
![servers and Bastion Host](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20181440.png)
## Webpage Output
![WebPage output](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175342.png)
## Its Working
![Successful Message](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20175025.png)
## Bastion Host
![Data Show through Bastion Host](https://github.com/deshmukhtanuja219-tech/-AWS-Three-Tier-Job-Portal/blob/main/Screenshot%202026-07-16%20174749.png)



