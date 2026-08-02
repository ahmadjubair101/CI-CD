# CI-CD

This repository showcases the projects, and the lessons and notes taken in the world of CI-CD mainly through the use of Github Actions.

# Key points

**Understanding the fundamentals of Continuous Integration and Continuous Deployment**

**Build simple CI/CD pipelines from scratch**

**Apply automated testing, linting and deployment workflows**

**Explain why CI/CD is critical in modern DevOps and production environments**

**Use CI/CD tooling confidently (GitHub Actions, GitLab CI,)**


# Projects


**Basic CI/CD Pipeline**- This was focused on creating a basic Continuous Integration (CI) pipeline using GitHub Actions for a Node.js application.

**Docker Build Pipeline**- This focused on creating a Docker Build Pipeline on Github Actions to verify if the application works whenever code is changed.

These included:

# Creating a simple Node.js project containing:

**app.js**

**package.json**

**package-lock.json**

**app.test.js**

**eslint.config.js**

**Configured ESLint to perform code linting.**

**Created unit tests for the application.**

**Built a GitHub Actions workflow (.github/workflows/task 1.yaml) that automatically runs whenever code is pushed or a pull request is opened.** 

# Created a Dockerfile to define how the application should be packaged into a Docker image.
This included:

**Built a GitHub Actions workflow (task 2.yaml) to automate the Docker build process.**

**Configured the workflow to trigger on GitHub events (such as push).**

**Used GitHub-hosted runners to perform the Docker build in a clean environment.**

**Verified that the Docker image builds successfully without actually deploying it.**'

**Troubleshooted common pipeline issues, including:

**Missing Dockerfile**

**Incorrect file names and paths**

**Workflow configuration errors**

**Repository structure issues**

# Configured the workflow on Project 1 to:

**Check out the repository.**

**Set up the required Node.js version.**

**Install project dependencies with npm install.**

**Run ESLint to check code quality.**

**Execute the unit tests.**

**Organised the project inside your repository and resolved issues caused by Git tracking the project as a submodule instead of a normal folder.**

# 

# Key CI concepts learned

**Continuous Integration (CI) – Automatically validating code whenever changes are pushed to a repository.**

**GitHub Actions – GitHub's built-in CI/CD platform for automating workflows.**

**Workflow – A YAML file that defines the automation process.**

**Job – A collection of steps executed on a GitHub runner.**

**Step – An individual task within a job, such as installing dependencies or running tests.**

**GitHub Runner – A virtual machine that executes your workflow.**

**Workflow Triggers – Events (such as push and pull_request) that start the pipeline automatically.**

**Working Directory – Running commands from the correct project folder when a repository contains multiple projects.**

**Dependency Installation – Installing required packages before building or testing the application.**

**Automated Code Validation – Ensuring code quality and functionality before changes are merged.**

# Tools and technologies used:

**Git – Version control.**

**GitHub – Source code hosting and collaboration.**

**GitHub Actions – CI automation platform.**

**Node.js – JavaScript runtime.**

**npm – Package manager for installing dependencies and running scripts.**

**ESLint – Static code analysis (linting).**

**Jest (or your chosen test framework) – Unit testing framework.**

**Docker – Containerisation platform.**

**Dockerfile – Image build instructions.**

**YAML – Used to define GitHub Actions workflows.**

**Visual Studio Code – Development environment.**

**Ubuntu (WSL) – Linux terminal environment used for development and Git commands.**
