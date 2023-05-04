# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)

<span style="font-size:24px">Project Name </span>
Building a Scalable and Fault-tolerant Kubernetes Cluster on AWS with Minikube

Project Description
This project aims to build a fault-tolerant Kubernetes cluster on AWS using Minikube, which is designed to be a lightweight and easy-to-install version of Kubernetes. Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

This project focuses on building a production-like Kubernetes cluster on AWS that can tolerate the failure of nodes in the cluster without loss of service. It also involves setting up a scalable infrastructure that can effectively handle the growing amount of traffic.

Project Architecture
The project architecture includes the following components:

AWS EC2 instances for Kubernetes cluster
AWS Elastic Load Balancer (ELB) for load balancing
AWS Route 53 for DNS management
Minikube for Kubernetes cluster setup
Getting Started
To get started with this project:

Clone this repository to your local machine using git clone <repo-link>.
Create an AWS account and configure your AWS CLI.
Install Minikube and start a Kubernetes cluster using minikube start.
Update the kubeconfig file to connect to your new cluster.
Run the kubectl commands to create a Kubernetes deployment and service.
Test the application by accessing the ELB URL or the Kubernetes service IP.
Prerequisites
To get started with this project, you will need:

An AWS account and access keys
AWS CLI installed on your local machine
Minikube installed on your local machine
Kubernetes CLI (kubectl) installed on your local machine
Authors
Dhananjay Kulkarni (@dhananjaykulkarni)
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Kubernetes documentation and community for the wealth of knowledge and support.
