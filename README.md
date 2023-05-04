# django-todo
# Project Name 
# Building a Scalable and Fault-tolerant Kubernetes Cluster on AWS with Minikube

# Project Description
This project aims to build a fault-tolerant Kubernetes cluster on AWS using Minikube, which is designed to be a lightweight and easy-to-install version of Kubernetes. Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

This project focuses on building a production-like Kubernetes cluster on AWS that can tolerate the failure of nodes in the cluster without loss of service. It also involves setting up a scalable infrastructure that can effectively handle the growing amount of traffic.

# Project Architecture
The project architecture includes the following components:

1. AWS EC2 instances for Kubernetes cluster
2. AWS Route 53 for DNS management
3. Minikube for Kubernetes cluster setup
## Getting Started
To get started with this project:

1. Clone this repository to your local machine using git clone <repo-link>.
2. Create an AWS account and configure your AWS CLI.
3. Install Minikube and start a Kubernetes cluster using minikube start.
4. Update the kubeconfig file to connect to your new cluster.
5. Run the kubectl commands to create a Kubernetes deployment and service.
6. Test the application by accessing the ELB URL or the Kubernetes service IP.
## Prerequisites
To get started with this project, you will need:

1. An AWS account and access keys
2. AWS CLI installed on your local machine
3. Minikube installed on your local machine
4. Kubernetes CLI (kubectl) installed on your local machine
## Authors
1. Shubham Londhe (@shubham1710) - Original Author
2. Dhananjay Kulkarni (@dhananjaykul) - Modifications and Deployment

## Acknowledgments
Kubernetes documentation and community for the wealth of knowledge and support.
Shubham Londhe for creating the initial version of this project.
