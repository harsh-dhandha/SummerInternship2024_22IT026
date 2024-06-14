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

### Day 3: Developing the Portfolio Website
⟢ Creating the Portfolio Structure:
- I started by setting up the basic structure of my portfolio using HTML, CSS, and JavaScript. This included defining the HTML elements for each section of the portfolio such as Home, About, Projects, and Contact.
- Implemented a responsive design using CSS to ensure the website looks great on both mobile and desktop devices. The design was developed with a Mobile First methodology, optimizing for smaller screens before scaling up to larger ones.

⟢ Adding Animations and Smooth Scrolling:
- Integrated animations that trigger on scrolling to add a dynamic and engaging feel to the website. These animations make the content appear smoothly as the user scrolls through each section.
- Implemented smooth scrolling to enhance the user experience, allowing seamless navigation between sections when clicking on navigation links.

### Day 4: Enhancing the Portfolio with Themes and Contact Functionality
⟢ Dark & Light Theme:
- Added functionality to toggle between dark and light themes, giving users the option to switch based on their preference. This involved creating two sets of CSS variables and JavaScript to handle the theme switching.
  
⟢ Contact Section and Email Sending:
- Developed the Contact section with a form that allows users to send emails directly from the website. Implemented email sending functionality using a JavaScript library such as EmailJS, which connects the form inputs to an email service.
- Ensured that the contact form is fully functional and user-friendly, with input validation and feedback messages to inform users of successful or failed submissions.

### Day 5: Configuration and Final Touchup
⟢ Configuring Security Group for Apache (Task 9):
- Set up the Security Group for the EC2 instance to allow HTTP traffic on port 80. This involved adding an inbound rule to ensure the Apache server is accessible from the internet.
⟢ Verifying the Configuration (Task 10):
 -Tested the setup by accessing the personal webpage hosted on the EC2 instance. Using the instance's public IP address, I confirmed that the Apache server was correctly serving the webpage, validating the successful configuration.

-Finalized Project:
Access the personal portfolio webpage [here](http://13.211.222.144/page.html)

## Additional Resources:
We were provided with a repository containing basic documentation of AWS services, which can be a valuable resource for anyone learning about AWS: [AWS Services Cheatsheet](https://github.com/hamidgholami/accp-cheatsheet).


## 2️⃣ Week 2
### *4th June 2024*
- *Online Session*: Learning about storage and S3 with its related services ,also swictching from EC2 to S3
- In the start of meeting we were asked rapid questions regarding week 1 tasks .
![AWS CLoudfront](https://miro.medium.com/v2/resize:fit:438/1*NiUh40Qs3iyzA4h30sr5SA.png)



### *Here is the Outine of Week-2:*
1. Create a Bucket
2. Make it private
3. Upload files
4. Encrypt the files
5. Create a Distribution 
6. Integrate it with S3
7. Create a new KMS Key
8. Change the Default Key for your bucket to this new key
9. Find out these events and logs for them in Cloudtrail
10. Shutdown the EC2 instance we created in first week

## 📝 Day-by-Day Progress

### Day 1: Launching into Amazon S3
- Today, I kicked off my exploration of Amazon S3! This powerful cloud storage service lets me store anything from vacation photos to critical business data.

⟢ *Created a new S3 bucket*:
- I started by creating a new Amazon S3 bucket. Think of it as a secure vault in the cloud, designed to hold all my important files. No more bulky hard drives – with S3, I can access my data from anywhere with an internet connection.
 
⟢ *Set the bucket's permissions to private*:
- Security is a top priority, so I configured the bucket to be private. This ensures that only authorized users can access the files I store inside. It's like having a personal safe deposit box in the cloud!
  
⟢ *Uploaded files to the bucket*:
- To get comfortable with S3, I uploaded some files to the bucket. This helped me understand how to upload data and test the access permissions I set.

### Day 2: Level Up Security and Speed with S3
- Today, I focused on making my S3 bucket even more secure and improving how content is delivered.

⟢ *Enabled encryption for the uploaded files*:
- First, I enabled server-side encryption for all the files stored in the bucket. This adds an extra layer of protection by scrambling the data before it's saved. It's like having a combination lock on your cloud vault – even if someone gains access, they won't be able to decrypt the files without the key!

⟢ *Created a CloudFront distribution and integrated it with the S3 bucket*:
- Next, I created a CloudFront distribution and linked it to my S3 bucket. CloudFront is a super-fast content delivery network from AWS that ensures users can access my files quickly and reliably, no matter where they are in the world. Imagine having multiple copies of your data stored around the globe – CloudFront delivers the closest copy to users, so they experience blazing-fast download speeds.
- CDN(Content Delivery Network) --

   <img src="https://d1.awsstatic.com/products/cloudfront/product-page-diagram_CloudFront_HIW.475cd71e52ebbb9acbe55fd1b242c75ebb619a2e.png" width="550" height="300"/>
   
### Day 3: Dialing in Security and Monitoring for My S3 Bucket
⟢ *Building a Secure Key Vault*: 
- I created a new key using AWS Key Management Service (KMS). Think of KMS as a secure vault specifically designed to manage and protect encryption keys. This centralized approach ensures even tighter control over how my data is encrypted.

⟢ *Upgrading Encryption with KMS*:  
- I configured my S3 bucket to use the new KMS key for encryption by default. Now, any new files uploaded to the bucket will be automatically encrypted using the KMS key, adding an extra layer of security.

⟢ *Keeping a Close Eye with CloudTrail*:
- To monitor activity around my S3 bucket and other AWS services, I started using CloudTrail. CloudTrail acts like a digital logbook, recording all API calls and user actions. This provides valuable insights for security analysis and helps ensure compliance with regulations.

⟢ *Smart Resource Management*:
- Finally, to optimize costs and avoid unnecessary charges, I shut down the EC2 instance I created in Week 1. This demonstrates the importance of managing resources effectively in the cloud.
