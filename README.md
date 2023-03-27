# Jenkins-CI-CD-Terraform-EKS

In this Project, we have created a Jenkins Pipline to deploy our dockerized nginx application using Terraform to our EKS Cluster. 

Here we have:
 - Initialised the AWS Infrastructure for our application, including entire network/ec2 configuration
 - Created Kubernetes Deployment which references our image from DockerHub
 - Created internal and external services to communicate with our configured pods in order for us to view from the web
 - Set up our Jenkins server to pull code from our Git repo, Installed the Terraform Plugin to be able to run commands and our Pipline Job
