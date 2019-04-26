# Showcase - Sample work

Following are the few technologies on which I have been doing my training and learning.
I have attached some of my sample work.

## [Ansible](https://github.com/venomwaqar/Sample-Work/tree/master/Ansible)

Ansible playbooks to configure 2 webservers and 1 Db server using modular struture (roles).
In addition to the infrastructure, a simple NodeJS application will also be installed on these webservers along with its connection to DB. 

## [CloudFormation](https://github.com/venomwaqar/Sample-Work/tree/master/CloudFormation)

Using cloudformation stacks to code VPC infrastructure.
Following are the components that will be configured using stacks:

* Public and private subnets
* Network ACL
* Route table
* Internet Gateway
* Nat Gateway
* Security Groups
* RDS - MySQL
* EC2 Instances
* Auto Scaling Group
* Load Balancer

A simple NodeJS application will also be install on EC2 instances using User Data (bash script)

## [Kubernetes](https://github.com/venomwaqar/Sample-Work/tree/master/Kubernetes)

Simple .yaml files to bring up the Wordpress application with its connection to MySQL along with HorizontalPodAutoscaler.

## [Dex - Gangway](https://github.com/venomwaqar/Sample-Work/tree/master/dex-gangway-configurations)

Basic .yaml files to configure and deploy DEX to use LDAP for OIDC authentication for kubernetes cluster. It also contains two client-apps, login-app and gangway to easily enable authentication flow for kubernetes cluster with DEX.
Good thing about gangway, after authentication it provides really easy kubectl related configurations, that will setup your local kubectl to easily connect with the remote kube-cluster.

## [Fabric8](https://github.com/venomwaqar/Sample-Work/tree/master/fabric-maven-sprint-boot)

Its a simple project, that will dockerize the JAVA application with tomcat/springboot.
It will use maven automation tools, in which pom.xml files will contains all the configuration. fabric8-docker-maven plugin will be use to build the image (using DockerFile) and tag and push the image to repository.