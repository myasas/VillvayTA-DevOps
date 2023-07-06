# VillvayTA-DevOps


Introduction
-------------------------------
This set up aims to build and deploy Villvay's TechAssesment to AWS Cloud infrastructure while adhering to following guidelines. 

**Immediate**
- [x] Used proper Git workflow: [Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- [X] Prepared level architectural overview of my deployment.

**Todo**
- [ ] Write terraform script
- [ ] Write ansible script for installing, configuring docker
- [ ] Write docker-compose file for running nginx container with volume mounting simple web interface and running containers.


#### **Prerequisites**
* Terraform
* Ansible
* AWS Cli 
* AWS "access key ID", "secret access key" for user with nessasary permissions
* Run time environment for make file

## Architecture

* **Architecture Diagram.** 
![Architecture Diagram](https://drive.google.com/uc?export=view&id=1RulPSHczD6SUCHZfyoQzVddkBAWoqCJW)

## Directory Structure
| Directory                | Purpose/Description                                                                                                                                              |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ansible](./ansible)     | Contains Ansible scripts required to configure the servers to run TechAssesment with my configuration                                                                   |
| [terraform](./terraform) | Contains Terraform modules and scripts needed to spin up infrastructure needed to implement infrastructure on which TechAssesments
| [docker-compose](./docker-compose) | Contains Docker compose scripts needed to spin up infrastructure needed to implement infrastructure on which TechAssesment



## Infrastructure Creation and Configuration

1. Simple command to see functionality of makefile
```shell
make
```
