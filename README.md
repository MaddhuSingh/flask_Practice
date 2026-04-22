**Jenkins CI/CD Pipeline for Flask Application** : This project demonstrates end-to-end CI/CD automation using Jenkins.

 **Project Overview**

This project demonstrates the implementation of a CI/CD pipeline using Jenkins for a Python Flask application. The pipeline automates the process of code integration, testing, and deployment.
The application used is a sample Flask app (forked from an existing repository), and the main focus is on DevOps automation using Jenkins.

___________________________________________________________________________________________________________________________________________________________

**Objective**

Automate build, test, and deployment process
Integrate GitHub with Jenkins
Implement CI/CD pipeline using Jenkinsfile
Configure email notifications for build status

____________________________________________________________________________________________________________________________________________________________

**Technologies Used**

Jenkins
Python (Flask)
Git & GitHub
Pytest
Email Extension Plugin (Jenkins)

_____________________________________________________________________________________________________________________________________________________________

**CI/CD Pipeline Stages**

1️- Checkout Code
Jenkins pulls code from GitHub repository
2️- Build
Install dependencies using requirements.txt
3️- Test
Run test cases using pytest
4️- Deploy
Application deployment step (basic execution)
5️- Post Actions
Send email notification on success/failure

_______________________________________________________________________________________________________________________________________________________________

**Project Structure**

flask_Practice/
│── app.py
│── requirements.txt
│── test_app.py
│── Jenkinsfile
│── templates/

_________________________________________________________________________________________________________________________________________________________________

**Jenkins Configuration**

Configured GitHub repository integration
Added credentials for secure access
Configured pipeline job
Installed Email Extension Plugin
Configured SMTP using Gmail

__________________________________________________________________________________________________________________________________________________________________

**Required Screenshots**

🔹 **Jenkins Pipeline Success**


<img width="940" height="452" alt="image" src="https://github.com/user-attachments/assets/6eacc0f8-e6f1-4fb3-b8a4-7232552a0fce" />


<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/bc182144-3a2b-41e1-8541-aea4d380c7a9" />


🔹** Email Notification**

<img width="940" height="360" alt="image" src="https://github.com/user-attachments/assets/2facc4df-cbfb-4f6d-b74f-19b71842e6fe" />


🔹 **Jenkins Configuration**

<img width="1895" height="810" alt="image" src="https://github.com/user-attachments/assets/87ec3a1e-a772-466e-817f-1de62096f4a5" />


<img width="1862" height="943" alt="image" src="https://github.com/user-attachments/assets/c9b8121a-c3ec-4be8-849e-337f1d294dad" />


___________________________________________________________________________________________________________________________________________________________________


**Email Notification Setup**

SMTP Server: smtp.gmail.com
Port: 587
Used App Password for authentication
Enabled TLS

___________________________________________________________________________________________________________________________________________________________________

**Results**

Pipeline executed successfully
Automated testing completed
Email notification received on build success

___________________________________________________________________________________________________________________________________________________________________

**Key Learnings**

Jenkins pipeline creation
CI/CD workflow automation
GitHub integration with Jenkins
Email notification setup
Handling dependencies and testing in CI

___________________________________________________________________________________________________________________________________________________________________

**Changes Done by Me**

Implemented Jenkins CI/CD pipeline
Configured automated testing
Added email notification functionality
Integrated GitHub with Jenkins

___________________________________________________________________________________________________________________________________________________________________

**Forked Repository URL**

https://github.com/MaddhuSingh/flask_Practice.git

___________________________________________________________________________________________________________________________________________________________________


**Conclusion**

**This project demonstrates how CI/CD pipelines can automate the software delivery process, improving efficiency and reducing manual effort.**

_**This project focuses on DevOps practices rather than application development.**_

___________________________________________________________________________________________________________________________________________________________________
