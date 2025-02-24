# Automated Flask App Deployment on AWS with Ansible

## Overview
This repository contains the Ansible playbook for automating the deployment of a Flask web application on AWS. 

The setup includes:
- **Two EC2 instances** hosting the Flask app.
- **AWS Load Balancer** and **Target Group** to manage traffic.
- **Ansible Playbook** to configure EC2 instances and deploy the app.

## Prerequisites
- AWS account with required permissions.
- Ansible installed on your local machine.
- Flask app repository to pull the latest code.

## Setup and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/mohameddoda7/aws-ansible-deployment.git
   cd aws-ansible-deployment
