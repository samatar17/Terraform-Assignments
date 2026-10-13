Assignment 1 – Deploying WordPress on AWS Using Terraform 
Project Overview
As part of my DevOps learning with CoderCo, I completed my first Terraform assignment, which involved deploying a fully working WordPress website on AWS.

The aim was to use Terraform to create the infrastructure, configure the server and automate the WordPress installation.

This assignment gave me the opportunity to put what I've been learning into practice and improve my understanding of Infrastructure as Code (IaC).

Technologies Used
Terraform
AWS EC2
AWS Security Groups
Ubuntu Linux
Apache2
MariaDB
PHP
WordPress
Bash scripting
VS Code
What I Did
Configured Terraform to work with AWS in the London region.
Created main.tf, variables.tf and outputs.tf.
Used Terraform to provision an EC2 instance.
Configured security groups to allow access to the web server.
Created a user data script to automate the installation of Apache, MariaDB, PHP and WordPress.
Used terraform plan to review my infrastructure before deploying it.
Successfully deployed the EC2 instance using terraform apply.
Completed the WordPress installation and accessed the admin dashboard.
Challenges and How I Solved Them 
1. EC2 instance deployment error

One of the first problems I encountered was during terraform apply. AWS rejected the instance because the instance type I selected wasn't eligible for the Free Tier on my account.

I checked the error message, investigated the available instance types and updated my Terraform configuration.

After making the changes, I ran Terraform again and successfully deployed the instance.

2. Apache default page instead of WordPress

After deploying my EC2 instance, I opened the public IP address expecting to see WordPress, but the Apache default page appeared instead.

I went back to my Terraform configuration and worked on the user data script to make sure WordPress was installed correctly, the database was configured and the required files were placed in the correct directory.

After resolving the issue, the WordPress installation page loaded successfully.

Final Result 
I successfully deployed a working WordPress website on AWS using Terraform.

I completed the WordPress setup, logged into the administration dashboard and confirmed that the website was accessible through the EC2 public IP address.

It was satisfying to see everything working, especially after troubleshooting the deployment issues.

What I Learned
This assignment helped me strengthen my understanding of:

Using Terraform to manage AWS infrastructure.
Working with Terraform variables, resources and outputs.
Automating software installation through EC2 user data.
Configuring Linux web servers and databases.
Reading error messages and troubleshooting deployment problems.
One of the biggest things I took away from this project was the importance of troubleshooting. Not everything worked the first time, but understanding what went wrong and making the necessary changes helped me complete the assignment.

I'm pleased with the progress I've made and looking forward to building on these skills in Assignment 2.

Assignment 1 – Successfully Completed! 

