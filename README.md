# aws-ec2-secure-web-server
🧠 Project: Secure Web Server on AWS EC2

📌 Objective

Deploy and secure a Linux-based web server on AWS using EC2.

🛠️ Technologies Used
AWS EC2
Ubuntu Linux
Nginx
SSH

🚀 Steps Performed
1. Launched EC2 Instance
Ubuntu Server
Configured key pair for SSH access

📸 Screenshot:


2. Connected via SSH
ssh -i key.pem ubuntu@public-ip

📸 Screenshot:


3. Installed Nginx
sudo apt install nginx -y
4. Configured Security Group
Allowed Port 80 (HTTP)
Allowed Port 22 (SSH)
5. Deployed Web Page
Edited /var/www/html/index.html

📸 Screenshot:


🔐 Security Considerations (you’ll add more later)
Controlled inbound traffic via security groups

📚 What I Learned
SSH access to cloud servers
AWS networking basics
Hosting a live web server
Don’t write like a tutorial blog
Don’t copy-paste random theory
Don’t skip screenshots
