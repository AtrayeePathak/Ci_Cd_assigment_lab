# CI/CD Lab Repository

**Name:** Atrayee Pathak  
**SAP ID:** 500105632  
**Batch:** B1 (DevOps)  

This repository contains all the lab exercises and documentation for the CI/CD (Continuous Integration and Continuous Deployment) course. Each lab focuses on different aspects of Jenkins, Maven, GitHub Actions, and other DevOps tools.

---

## Lab Exercises Overview

### 1. **Email Notification in Jenkins**
- **Objective:** Configure email notifications in Jenkins for build status updates.
- **Key Steps:**
  - Install the Email Extension Plugin.
  - Configure SMTP settings.
  - Set up post-build actions to send emails.

---

### 2. **CICD Pipeline Security**
- **Objective:** Implement security practices in a Jenkins pipeline.
- **Key Steps:**
  - Install required plugins (e.g., Credentials, OWASP Dependency-Check).
  - Write a Jenkins pipeline script with secure environment variables.
  - Validate pipeline execution.

---

### 3. **Integrate Maven with Jenkins**
- **Objective:** Set up a Maven project in Jenkins for automated builds.
- **Key Steps:**
  - Install the Maven Integration Plugin.
  - Configure global tools (JDK, Maven, Git).
  - Create a Maven project and trigger builds.

---

### 4. **Poll SCM Configuration in Jenkins**
- **Objective:** Automate builds using Poll SCM to detect repository changes.
- **Key Steps:**
  - Configure a freestyle project with Git SCM.
  - Set up Poll SCM with a cron schedule (e.g., `H/2 * * * *`).
  - Verify builds trigger on Git commits.

---

### 5. **Remote Triggering of Parameterized Builds**
- **Objective:** Trigger Jenkins builds remotely with custom parameters.
- **Key Steps:**
  - Install the "Build With Parameters" plugin.
  - Define a string parameter (`my_param`).
  - Trigger builds using `curl` (e.g., `curl -X POST http://JENKINS_URL/job/JOB_NAME/buildWithParameters?my_param=value`).

---

### 6. **Groovy Scripting in Jenkins**
- **Objective:** Automate tasks using Groovy scripts in Jenkins pipelines.
- **Key Steps:**
  - Clone a Git repository.
  - Take user input (e.g., numbers for a calculator).
  - Compile and run a Java program.
  - Clean up directories post-execution.

---

### 7. **Multibranch Pipeline in Jenkins**
- **Objective:** Configure a Jenkins multibranch pipeline for automated branch builds.
- **Key Steps:**
  - Fork/clone a sample repository.
  - Create a `Jenkinsfile` with stages for checkout, build, test, and deploy.
  - Set up a multibranch pipeline job in Jenkins.

---

### 8. **SAST with Snyk in Jenkins**
- **Objective:** Integrate Snyk for Static Application Security Testing (SAST).
- **Key Steps:**
  - Install the Snyk Security Plugin.
  - Configure Snyk API token in Jenkins credentials.
  - Add a Snyk scan step in the pipeline.

---

### 9. **GitHub Actions Workflow**
- **Objective:** Create a basic CI workflow using GitHub Actions.
- **Key Steps:**
  - Set up a `.github/workflows/basic-workflow.yml` file.
  - Define jobs to run on `push`/`pull_request` events.
  - Monitor workflow execution in the GitHub Actions tab.

---

### 10. **Git Collaboration Scenario**
- **Objective:** Practice Git workflows (fork, branch, PR, merge).
- **Key Tasks:**
  - Fork a repository, create branches, and modify files.
  - Resolve merge conflicts.
  - Sync forks with upstream changes.

---


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/AtrayeePathak/CI-CD-Lab.git

---
## Tools Used
Jenkins (Pipeline, Plugins)

Maven (Build Automation)

Git/GitHub (Version Control)

Snyk (Security Scanning)

GitHub Actions (CI/CD)

### Key Features of This README:
1. **Structured Overview**: Clearly lists each lab with objectives and steps.
2. **Repository Navigation**: Helps users locate specific labs easily.
3. **Tool Highlights**: Showcases the DevOps tools used.
4. **Clarity**: Concise yet comprehensive for both evaluators and peers. 
