# terraform
Infrastructure as Code with Terraform by Nana

Infrastructure as Code simply means scripting the creation and configuration of your infrastructure.

## This course will cover 

- **Introduction to Terraform**
- **Providers**
- **Resources and data sources**
- **Introduction to Terraform**
- **Terraform State**
- **Output**
- **Environmental Variables**

- **DEMO PROJECT 1: Automate creating an EC2 Server on AWS with firewall and other networking configuration using terraform**
- **Learn how to make terraform configuration reuseable and modular using terraform modules. How to modularize our own projects as well as how to use existing modules from the terraform registry in our projects**

- **DEMO PROJECT 2: USe existing modules to automate provisioning of EKS Cluster on AWS Using Terraform**

- **DEMO PROJECT 3: Integrating Terraform in JJenkins CICD pipeline to automate proviioning infrastructure on AWS before deploying the newly built application**

![image](./images/Snipaste_2025-01-04_15-22-27.jpg)
![image](./images/provisioning.jpg)


**What is Terraform?**

Terraform alows you to automate and manage your infrastructure, platform and services that run on that infrastructure. It is open source, and uses declarative language.

Declarative language meaning you don not have to define every step on how this automation and infrastructure management is done. You just define the final and end result and terraform will figure out how to execute it. ***Declarative: this means you define what end result you want*** Imperative language means you define exact steps on how you want the result.
***Terraform is a tool for infrastructure provissioning***

It is suitable to note that infrastruture provissioning should be done in the correct order. Because one task may depend on the other.

### Difference between Ansible and Terraform 
Firat of all,
1. Both Ansible and terraform are Infrastructure as a code (IAC) tool. But however, Terraform is mostly used for Infrastructure provissioining. Meaning they are both used to automate the provissioning, configuring and managing of infrastructure.

However, ***terraform is mainly used as an infratructure provissioning tool**. that's where it's main power lies. it also has the capability to deploy applications in other tools o that infrastructure.

Ansible on the other hand is mainly a ***configuration management tool** so once the infrastructure is provissioned, ansible can now be used to configure the infrastructure, deploy applications on it, install and update softawres on that infrastructure, etc.

- ### Preparing infrastructure (for example on the aws cloud platform) for deploying applciations entails that:
1. Prepare your network space (Private or public network, VPC,)
2. Create users and permissions
3. Create/provission EC2 server instance
4. Install Docker and other tools (if needed) and any other tool you might need for your application.
5. Setup Security like; networks, firewalls, etc.

Once your infrastruture is prepared, the developer can now deploy the docker application on the prepared infrastructure. 

