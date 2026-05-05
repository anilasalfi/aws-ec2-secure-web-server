# aws-ec2-secure-web-server
## Project: Secure Web Server on AWS EC2

**Objective**  
Deploy and secure a Linux-based web server on AWS using EC2.

**Technologies Used**
- AWS EC2
- Ubuntu Linux
- Nginx
- SSH

**Steps Performed**
1. Launched EC2 Instance  
Ubuntu Server  
Configured key pair for SSH access  

<img width="1350" height="563" alt="image" src="https://github.com/user-attachments/assets/e280f47c-5697-40d4-b16d-407af4deef18" />  
  
2. Connected via SSH  
ssh -i MyFirstKey.pem ubuntu@16.171.17.40  

<img width="1083" height="553" alt="image" src="https://github.com/user-attachments/assets/4d4c58c7-2945-4b4f-87f9-314136138bf9" />  


3. Installed Nginx  
sudo apt install nginx -y

5. Configured Security Group  
Allowed Port 80 (HTTP)  
Allowed Port 22 (SSH)  

7. Deployed Web Page  
Edited /var/www/html/index.html
<img width="1357" height="671" alt="image" src="https://github.com/user-attachments/assets/71daad88-5955-4650-8dc8-d535bc7bd085" />


🔐 Security Considerations  
Controlled inbound traffic via security groups

📚 What I Learned  
SSH access to cloud servers  
AWS networking basics  
Hosting a live web server  
Don’t copy-paste random theory
Don’t skip screenshots
