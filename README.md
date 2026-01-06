# Mini Project: Web Hosting on AWS EC2 with EBS Backup

## Project Overview
This project demonstrates hosting a static website on an AWS EC2 instance with persistent storage using EBS volume.  
It covers EC2 launch, Apache installation, website deployment, and data backup using EBS snapshots.

## AWS Services Used
- Amazon EC2 (Instance launch & configuration)  
- Amazon EBS (Volume attachment & backup)  
- Security Groups (HTTP & SSH access)  
- Apache Web Server  

## Implementation Steps
1. Launched an Amazon EC2 instance using Amazon Linux.  
2. Configured security group to allow HTTP and SSH access.  
3. Attached an EBS volume to the EC2 instance for persistent storage.  
4. Installed Apache web server on the EC2 instance.  
5. Deployed static website files to the server.  
6. Created an EBS snapshot for backup and data recovery.  
7. Tested website using the public IP of EC2 instance.  

## Backup / Proof
Website data is stored on EBS volume and backup is taken using EBS snapshot.  
Screenshots of the setup and steps are saved in a Word file for reference.

## Outcome
Successfully hosted a static website on AWS EC2 with reliable storage and backup.  
The project demonstrates basic AWS cloud deployment workflow and data reliability using EBS.
