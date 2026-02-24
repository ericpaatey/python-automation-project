# python-automation-project
<strong>TECH STACK</strong>: Terraform • AWS ECS/Fargate • Docker • GitHub Actions <br><br>
<strong>PROJECT DESCRIPTION:</strong><br>
The project comprises:<br>
 - a python-based web app with a Dockerfile for deployment as a containerized application on
AWS Elastic Container Service (ECS). <br>
 - an AWS environment provisioned using using Terraform, an Infrastructure as Code (IaC) tool.The Terraform script provisions AWS Services such as VPC, ECS, ECR, load balancer, and
CloudWatch (for logging/monitoring) needed to run the web app. <br>
 - A CI/CD pipeline built on GitHub Actions which automatically deploys the app to the AWS
provisioned infrastructure. <br><br>
<strong>BENEFITS:</strong><br>
 - Eliminates manual deployments and any configuration drift.<br>
 - The entire stack is reproducible in minutes.<br>
