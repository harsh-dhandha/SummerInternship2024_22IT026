# SummerInternship2024_22IT026
<h2>4th Sem Summer Internship</h2>
# 🌟 AWS Summer Internship 2024 - Project Showcase 🌟

Welcome to my GitHub repository for the AWS Summer Internship 2024! This project showcases the work done during the internship, including practical insights and hands-on experience with Amazon Web Services (AWS). 

## 🚀 Introduction

### **25th May 2024**
- **AWS Bootcamp Live Session**: Basics of Amazon Web Services
- On 25th may, there was a live bootcamp which Amit Arora(Security Architect at AWS) is doing for an AWS Club where entry level engineers can participate and build there AWS skills from groundsup.. So it wasn't the start of internship but we learnt the basics of amazon web services , how it provides various functionalities to developers.
The internsip period is of 4 weeks with focus on Labs and Practical Insights to make familiar with aws.

# Start of Internship

## 1️⃣ Week 1
### **28th May 2024**
- **Orientation Meeting**: Introduction to AWS and overview of the internship tasks
- At the start of meeting I tackled questions regarding aws to know its base. Then the 1st week agenda regarding the tasks to be done was discussed. The tasks including from the start of creating an account to generating a portfolio hosted on a aws instance.

![AWS Bootcamp](https://c.tenor.com/GO7C6FD0y3YAAAAC/tenor.gif)

### **Here is the Outine of Week-1:**
1. Create an AWS Free Tier account
2. Log on to the AWS Console
3. AWS Billing and Cost Management
4. Set up a zero-dollar limit budget
5. Launch an EC2 Instance
6. Connect to the EC2 Instance
7. Install Apache Web Server on the Linux Instance
8. Deploy a `personalpage.html` on Apache
9. Open Security Group for Apache to accept connections on port 80
10. Access the `personalpage.html` using the public IP address of the EC2 instance.

## 📝 Day-by-Day Progress

### Day 1: Creating AWS Free Tier Account
- Created an AWS Free Tier account as part of Task 1.
- Logged on to the AWS Console (Task 2).
- Explored AWS Billing and Cost Management (Task 3).
- Set up a zero-dollar limit budget (Task 4).
- Launched an EC2 instance from the free tier options (Task 5).

### Day 2: 
- Connected to the EC2 Instance (Task 6):
After launching the EC2 instance, I connected to it using SSH. This allowed me to access the virtual server, which is essentially a remote computer running on AWS infrastructure. The connection was established securely using the provided key pair, ensuring that my data remains protected.
(-Commands : 
shell- to write command in it
pwd-current web directory
whoami-this will which user is as logged in this account )

- Installed an Apache Web Server on the Linux Instance (Task 7):
Once connected, I installed Apache, a widely-used open-source web server software. Apache is crucial for serving web pages to users. The installation involved updating the package repositories and using package management commands to install Apache on the Linux-based EC2 instance.
(-Commands : sudo su-to elevate your credentials to root
yum install -y httpd- to install apache web server(Linux server)
cd /var/www/html- to create a HTML file into directory)

- Deployed a Personal page.html on Apache (Task 8):
With Apache running, I deployed a simple HTML page (page.html). This involved placing the HTML file in Apache’s root directory and configuring the server to serve this page. Deploying the HTML page allowed me to create a personal webpage accessible over the internet via the EC2 instance's public IP address.

