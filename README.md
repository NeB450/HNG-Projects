# Prerequisites
**Before i began, i ensure i had the following:**

- Redhat machine as my OS for my AWS EC2 instance.
- My html, css and javascript static web application files ready to be deployed.

## Procedures for Deployment 
### 1. My Static Web Application
-  HTML files: index.html, bio.html, project.html
-  CSS files: styles.css
-  JavaScript files: app.js
### 2. Moving Files to my Aws Server ###

- I ssh into my EC2 instance using the public IP of my EC2 instance
- Used yum command to install httpd service on my redhat machine
- I entered into the /var/www/html/ folder
- i created and added the codes for my index, bio, project files using vim editor

### 3. Configuring, Enabling and Starting the Apache service
- I run the systemctl command to start httpd service
- After which i ran systemctl command to enable the httpd service

### 4. Accessing/Testing My Web Application
- I accessed my web application through my browser using the ip address of my ec2 instance 54.227.201.231
## COMMANDS USED
 - yum install httpd -y
- systemctl start httpd
 - systemctl enable httpd

 - cd /var/www/html
 - vi index.html
 - vi bio.html
-  vi project.html
-  vi styles.css
-  vi app.js