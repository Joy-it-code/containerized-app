# Project Title: Containerization and Container Orchestration

## Introduction

As an aspiring DevOps engineer, understanding containerization and orchestration is crucial to managing modern software development workflows effectively. This project serves as a stepping stone in mastering key DevOps tools like Docker and Kubernetes. By containerizing a simple static website and orchestrating its deployment in a Kubernetes cluster, I aim to gain hands-on experience with core concepts of infrastructure automation, scalability, and deployment pipelines. This project will help me build the foundational skills required to handle real-world challenges in DevOps environments.

## Objectives

+ Develop Expertise in Containerization.

+ Familiarize with Docker Hub.

+ Set Up and Operate a Kubernetes Cluster.

+ Deploy and Manage Applications in Kubernetes

+ Enhance Debugging and Accessibility Skills

+ Learn best practices in containerization and orchestration to prepare for more advanced DevOps tools and workflows.

## Step-by-Step Implementation

### Step 1 : Project setup

+ Note: For this project, I am using Git Bash on a Windows workstation to execute these shell commands, as it provides a Unix-like command-line experience. Open your Git bash terminal.

### Step 1.1: Create project directory named Containerized-app and navigate into it.

**Commands:**

```
mkdir Containerized-app
cd Containerized-app
```
![](./img/1.mkdir.png)

### Task 1.2: Build the web application

+ Create HTML and CSS files with the following content:

**index.html:**
command:

```
vim index.html
```

![](./img/2.index.file.png)


**style.css:**

```
vim style.css
```

![](./img/2b.style.file.png)


### Step 2:

#### Task 2.1: Initialize, Add and Commit Git Repository

+ Initialize a Git repository for version control

**code**

```
git init
git add .
git commit -m "Initial commit - basic static website"
```