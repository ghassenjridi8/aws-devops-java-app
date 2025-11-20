# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app deployment and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction

This project provides an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.  
The deployment pipeline around the Java web app in this repo is invisible to the end user but makes a huge impact by automating the software release process.

- I’m doing this project to learn more about CI/CD and gain hands-on experience automating the flow from code development to deployment.

<br>

## Technologies

Here’s what I’m using for this project:

- **Amazon EC2**: I’m developing my web app on Amazon EC2 virtual servers so that software development and deployment happen entirely in the cloud.  
- **Key pairs, SSH connections, Git, Maven, and Java**
- **VS Code**: For my IDE, I chose VS Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.  
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.  
- **AWS CodeArtifact**: CodeArtifact stores my artifacts and dependencies, which helps with high availability and speeds up my project’s build process.  
- **AWS CodeBuild**: Once it’s rolled out, CodeBuild will take over my build process. It will compile the source code, run tests, and produce ready-to-deploy software packages automatically.

<br>

## Setup

To get this project up and running on your local machine, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ghassenjridi8/aws-devops-java-app.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd aws-devops-java-app
    ```

3. **Install dependencies:**
    ```bash
    mvn install
    ```

<br>

## Contact

If you have any questions or comments about my CI/CD project, please contact:  
**Ghassen** – [Jridi59@gmail.com](mailto:Jridi59@gmail.com)  
- [LinkedIn]() *(Add your LinkedIn link here)*

<br>

## Conclusion

Thank you for exploring this project! I’ll continue to build this pipeline and apply my learnings to future projects.
