# aws-ec2-secure-web-server
## Project: Secure Web Server on AWS EC2  

*Created: 5 May, 2025 | Last Updated: 6 May, 2025*

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


4. Configured Security Group  
Allowed Port 80 (HTTP)  
Allowed Port 22 (SSH)
<img width="1052" height="199" alt="Screenshot 2026-05-05 214823" src="https://github.com/user-attachments/assets/e635e5c7-67d0-4208-8584-3bcc50db2387" />


5. Deployed Web Page  
Edited /var/www/html/index.html
<img width="1357" height="671" alt="image" src="https://github.com/user-attachments/assets/71daad88-5955-4650-8dc8-d535bc7bd085" />  


6. Enabled Firewall  

<img width="1101" height="370" alt="Screenshot 2026-05-05 214857" src="https://github.com/user-attachments/assets/4c6239d4-6444-45d9-801a-11ca5c250bd8" />

<br/>

**Security Enhancements**  
- Controlled inbound traffic via security groups
- Disabled password authentication
- Disabled root login
- Configured UFW firewall
- Restricted SSH access to specific IP
- Installed Fail2Ban

**What I Learned**    
1. SSH access to cloud servers  
2. AWS networking basics  
3. Hosting a live web server  
4. Hardening the server

<!-- This content will not appear in the rendered Markdown -->
