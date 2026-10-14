I'm happy to have successfully completed my second Terraform assignment!
The aim of this assignment was to use Terraform to automatically deploy an EC2 instance on AWS and use cloud-init to install and configure NGINX without doing everything manually.
It was a great experience seeing how automation can make deploying cloud infrastructure much easier!

 What I Did and Achieved
Created a cloud-init.yaml file to automatically install and configure NGINX.
Created a main.tf file containing my Terraform configuration.
Configured AWS to launch an Ubuntu EC2 instance in the London region.
Created a security group to allow HTTP traffic so the website could be accessed.
Used terraform init to initialise the project.
Ran terraform validate and successfully checked my configuration.
Used terraform plan to preview the AWS resources.
Ran terraform apply and successfully deployed two AWS resources.
Used cloud-init to automatically install NGINX and create a custom webpage.
Opened the website in my browser and successfully saw "Terraform Assignment 2 Successful!"
Finally, used terraform destroy to remove both AWS resources after completing my testing.
 What I Learned
This assignment helped me understand how Terraform and cloud-init work together.

I learned how to automate the creation of cloud infrastructure, install software automatically when a server starts, configure security groups, and test that everything is working correctly.
I also became more confident using Terraform commands and understanding the different stages of deploying infrastructure.

 Final Result
✅ EC2 instance deployed successfully
✅ NGINX installed automatically using cloud-init
✅ Custom website running successfully
✅ No manual server configuration needed
✅ AWS resources destroyed after testing

I'm really pleased with what I've achieved in this assignment. Seeing my website working after deploying everything through Terraform was a great feeling.
