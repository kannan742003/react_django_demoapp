# Jenkins CI/CD Pipeline with GitHub Webhook Integration for Docker App Deployment on EC2
## Project Overview
This project demonstrates the setup of a Jenkins CI/CD pipeline with GitHub webhook integration to automate the deployment of a Docker application on AWS EC2 instances. The project focuses on streamlining the development and deployment process, ensuring that changes pushed to the GitHub repository are automatically reflected in the live web application.
## Prerequisites

Before you start, make sure you have the following prerequisites in place:

- An AWS account to create and manage EC2 instances.
- An SSH key pair for secure access to the EC2 instance.
- Docker and Docker Compose installed on the EC2 instance.
- A GitHub repository containing the application code.
- Jenkins installed and configured on an EC2 instance.

Note: Detailed instructions for setting up the prerequisites are provided in the project implementation steps.
## Project Steps

Follow these steps to implement the project:

1. Create an AWS EC2 instance with the specified configuration.
2. Install Jenkins and Docker on the EC2 instance.
3. Configure security groups to allow traffic on ports 8080 and 8001.
4. Access the Jenkins portal, install plugins, and set up the initial admin user.
5. Create a CI/CD pipeline in Jenkins to fetch code from your GitHub repository.
6. Add GitSCM polling to trigger pipeline builds on code commits.
7. Configure GitHub webhook integration for real-time updates.
8. Install the Git Integration plugin in Jenkins for seamless Git integration.
9. Set up SSH and GPG keys for secure communication with GitHub.
10. Create a webhook in your GitHub repository to trigger pipeline builds.
11. Save the Jenkins project configuration.
12. Push changes to your GitHub repository to trigger automated pipeline builds and deploy the application.

