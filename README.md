# Sprints-DevOps-Final-Project
Sprints DevOps Final Project
I'm glad to say that I finished the last DevOps project at Sprints:
  
🛠️ Used the following tools and technologies:  
- Terraform 🌍  
- Ansible 🤖  
- Jenkins 🚀  
- Docker 🐳  
- Kubernetes 🚢  
- AWS 🌐  
- Python 🐍  
  
📝 Created Terraform scripts to:  
- Create a VPC with 3 subnets  
- Create a private EKS cluster with 2 nodes  
- Create an EC2 instance for Jenkins  
- Create an ECR registry with 2 repo one for the database and another one for Python App  
  
🤖 Used Ansible to:  
- Install and configure Jenkins  
- Create an admin user for Jenkins  
- Install necessary plugins for Jenkins  
  
🚀 Created Kubernetes files for:  
- Deployment of the Python code  
- StatefulSet for MySQL using PV and PVCs  
- Services for both the database and code  
- ConfigMaps and secrets for the code  
- Ingress using NGINX controller  
  
🎉 Build the CI/CD Pipeline using Jenkins.  
- Checkout external project  
- build new Docker images  
- push the image to ECR  
- add an image to the YAML files app and database  
- Deploy Kubernetes manifest files. 🚀  
- the pipeline is configured to output the URL to the website.
