# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction
I’m working on this project to deepen my DevOps skills by building a fully automated CI/CD pipeline using AWS and GitHub.  
It aligns with my career goal of mastering practical end-to-end deployment workflows and boosting deployment efficiency.

This project introduces how to build and deploy a Java-based web app using AWS CI/CD tools. The pipeline I’m building is invisible to the end user but greatly improves delivery speed and consistency.

<br>

## Technologies
Here’s what I’m using for this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- **VS Code**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **[COMING SOON] AWS CodeArtifact**: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **[COMING SOON] AWS CodeBuild**: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **[COMING SOON] AWS CodeDeploy**: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.
- **[COMING SOON] AWS CodePipeline**: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.


<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nextwork-web-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

<br>

## Contact
If you have any questions or comments about the NextWork Web Project, please contact:
Vijay Pratap Singh Hada - vijaypratapsinghhada9@gmail.com(mailto:your.email@email.com)

<br>

## Conclusion
Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects.

A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project guide and support. [You can get started with this DevOps series project too by clicking here.](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)

