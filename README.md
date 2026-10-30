# CI/CD Final Project

## Project Name
**CI/CD Pipeline for Python Application Deployment using GitHub Actions, Tekton and OpenShift**

## Project Overview
This project demonstrates the implementation of an automated Continuous Integration and Continuous Delivery (CI/CD) pipeline for a Python application.

The pipeline uses GitHub Actions to automate code validation and unit testing. Tekton is used to define and execute reusable pipeline tasks, while Red Hat OpenShift provides the platform for building and deploying the application.

The main objective is to improve software delivery by automating repetitive development, testing and deployment activities.

## Technologies Used

- **Programming Language:** Python
- **Version Control:** Git and GitHub
- **CI:** GitHub Actions
- **Code Linting:** Flake8
- **Unit Testing:** Nose
- **CI/CD Pipeline:** Tekton
- **Container Build:** Buildah
- **Deployment Platform:** Red Hat OpenShift
- **Container Orchestration:** Kubernetes

## Project Objectives

1. Automate code validation using GitHub Actions.
2. Perform Python code linting using Flake8.
3. Execute unit tests using Nose.
4. Create reusable Tekton tasks for pipeline execution.
5. Build application container images using Buildah.
6. Deploy the application using OpenShift Pipelines.
7. Automate the complete CI/CD workflow.

## CI/CD Workflow

The project follows these major stages:

1. **Cleanup:** Clean the pipeline workspace.
2. **Git Clone:** Retrieve the source code from GitHub.
3. **Linting:** Check code quality using Flake8.
4. **Unit Testing:** Execute automated tests using Nose.
5. **Build:** Build the container image using Buildah.
6. **Deployment:** Deploy the application to OpenShift.

## Project Structure

```text
cicd-final-project/
│
├── .github/
│   └── workflows/
│       └── workflow.yml
│
├── .tekton/
│   └── tasks.yml
│
├── README.md
└── application source and test files
```

## Expected Outcome

The project aims to establish an automated CI/CD pipeline that validates application code, runs unit tests, builds a container image and deploys the application to an OpenShift environment.

## Project Status

In Progress
