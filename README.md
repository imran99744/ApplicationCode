# Deploying Dockerized App on AWS EKS Cluster using ArgoCD and GitOps methodology with CircleCI

## Introduction

This repository contains the documentation and source code for a hands-on project that demonstrates GitOps and ArgoCD principles. The project focuses on containerizing a web application, provisioning a Kubernetes cluster on AWS Elastic Kubernetes Service (EKS) using Terraform, and implementing Continuous Integration and Continuous Deployment (CI/CD) using ArgoCD.

## Project Overview
In this project, I've created a complete workflow for deploying a web application on Kubernetes using GitOps practices with ArgoCD. Here's a high-level overview of the project:

1. Dockerized Web Application: The web application source code is containerized using Docker, ensuring portability and consistency.
2. Kubernetes Cluster Provisioning: We provision a Kubernetes cluster on AWS Elastic Kubernetes Service (EKS) using Terraform. The infrastructure is defined as code, making it easy to manage and scale.
3. CI/CD with ArgoCD: We set up a CI/CD pipeline using ArgoCD. Changes to the application code trigger automatic deployments, ensuring a smooth and efficient development process.
4. Security Measures: Security best practices are implemented throughout the project, including network policies, RBAC, and secrets management.
5. Best Practices: The project adheres to Kubernetes and GitOps best practices, promoting reliability, scalability, and maintainability.

## Architecture
![Architecture Diagram](https://cdn-images-1.medium.com/max/800/1*T5IRoSoiqT8qnYLUprsRUQ.png)

## List of AWS services
- Amazon EKS 
- Amazon VPC
- Amazon  IAM
- Amazon EC2
- Amazon Autoscaling 
- Amazon S3
- DynamoDB 

## Tech stack

- React Js


## This project contains another two GitHub repositories

➡️ [Terraform code] (https://github.com/imran99744/App-tf-code)

➡️ [Manifest Repo] (https://github.com/imran99744/kube-manifest)
