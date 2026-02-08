# Jenkins CI/CD Pipeline for AWS S3 Deployment

## Project Overview
This project demonstrates an end-to-end CI/CD pipeline using Jenkins to automatically deploy a static website to AWS S3.

Whenever code is pushed to GitHub, Jenkins pulls the latest code and deploys it to an S3 bucket.

## Architecture
GitHub → Jenkins (EC2) → AWS S3 → Static Website Hosting

## Tools & Technologies
- Jenkins
- AWS EC2
- AWS S3
- AWS IAM
- Git & GitHub
- AWS CLI

## Features
- Automated deployment using Jenkins pipeline
- GitHub integration with Jenkins
- Secure AWS access using IAM
- Static website hosting on AWS S3
- Continuous Integration and Continuous Delivery (CI/CD)

## Setup Steps

1. Launch EC2 and install Jenkins
2. Install AWS CLI on Jenkins server
3. Configure AWS credentials using:
4. Create an S3 bucket and enable static website hosting
5. Create Jenkins Pipeline job and connect this repository
6. Run the pipeline to deploy website automatically

## Output
Website will be available using the S3 static website endpoint.

## Author
Pradeep Kumar
DevOps Beginner Project
