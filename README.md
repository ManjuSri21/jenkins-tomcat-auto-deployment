## Project Title
CI/CD Automation: Jenkins-based Auto Deployment to Apache Tomcat

## Description
This project demonstrates automated deployment of a Java WAR application
to Apache Tomcat using Jenkins CI/CD pipeline.
The goal is to eliminate manual deployment and achieve continuous deployment through Jenkins.


## Tools Used
- Jenkins
- Apache Tomcat 9
- Git & GitHub
- Linux (Ubuntu)


<img width="1536" height="1024" alt="Automated WAR deployment flowchart" src="https://github.com/user-attachments/assets/c8664f12-0208-4aba-a881-d49edbeddf4f" />


## Steps Involved

1. Install Jenkins and Apache Tomcat on Ubuntu server

2. Change Tomcat default port to avoid conflict with Jenkins

3. Configure Jenkins Freestyle job

4. Install Deploy to Container plugin

5. Configure Tomcat credentials with manager-script role

6. Deploy WAR file automatically

7. Verify application via browser



# Jenkins Email Notification Setup

## Purpose

To receive email alerts when Jenkins build or auto deployment fails.


## Configuration Steps

1. Install Email Extension plugin in Jenkins

2. Configure SMTP server (smtp.gmail.com)

3. Enable SSL and SMTP authentication

4. Generate Gmail App Password

5. Configure Post-build action → Email Notification

6. Test configuration by triggering build failure
