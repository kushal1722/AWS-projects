# Hosting a Website on AWS EC2

## Overview
This project demonstrates how to launch an EC2 instance using an IAM user and host a simple website. The website is accessible via the **public IP address** of the EC2 instance.

## Steps:
1. Created an **IAM user** and added it to the **IT group**.
2. Launched an **EC2 instance** using the IAM user.
3. Configured **security groups** to allow **HTTP (port 80)** traffic.
4. Used **user data** to install and configure a web server automatically during the launch of the instance.
5. **Hosted a website** under the **public IP** of the EC2 instance.

## Technologies Used:
- AWS EC2
- IAM
- Linux (Amazon Linux)
- Apache
- Bash (User Data Script)
