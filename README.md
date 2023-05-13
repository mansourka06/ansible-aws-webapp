# ansible-aws-webapp
Deploy an conternerize Web Application in AWS EC2 using Ansible and Docker. 


## Descritpiton :

- In this repository is setup a deployment of a Containerized Web Application in AWS EC2 using Ansible and Docker.
- This guide describes how to deploy a containerized web application in AWS EC2 using Ansible and Docker. The process involves setting up an EC2 instance, installing Docker and Ansible, configuring the EC2 instance for Ansible access, and running an Ansible playbook to deploy the web application.

## Prerequisites :

- An AWS account
- Basic knowledge of AWS EC2 and Ansible
- An SSH key pair

## Workflow :

- Install local prerequisites packages
- Create AWS EC2 Server
- Deploy the webapp
    * Install Apache using docker in the EC2 Server
    * Create Apache container

## Usage :

- Clone the repository with the command: 
    * git clone https://github.com/mansourka06/ansible-aws-webapp.git

- Run the Ansible playbook to deploy the web application:
    * ansible-playbook -i localhost deploy.yml

- To run only tasks with a specific tag, use the --tags option with the ansible-playbook command. For example, to only run tasks with the docker tag, run the following command:
    *   ansible-playbook -i localhost deploy.yml --tags docker


## Author :

- Mansour KA: [jr Cloud DevOps Engineer and IT Passionate]()
