# NopCommerce Project
Jenkins CI/CD Pipeline — nopCommerce E2E Testing
A CI/CD pipeline built with Jenkins that automates end-to-end test execution for the nopCommerce e-commerce platform. Tests are triggered automatically on each code commit, with results reported after every run.

**Project Overview**
Item                     Details
Application              nopCommerce
CI/CD tool               Jenkins
Test framework           Java + Selenium / TestNG
Build tool               Maven
Trigger                  On every commit to the main branch

**What This Project Does**
This project integrates automated tests into a Jenkins pipeline so that:

Every code commit automatically triggers the full test suite
Test results are generated and available after each build
Failed tests are immediately visible without manual intervention

Test Coverage

User login and authentication
Product browsing and search
Add to cart flow
Checkout process
User registration

**Tech Stack**
Jenkins — CI/CD automation server
Java — Test scripting language
Selenium WebDriver — Browser automation
TestNG — Test framework and reporting
Maven — Build and dependency management
nopCommerce — Application under test

**Setup & Configuration**

Prerequisites
Jenkins is installed and running
Java 11+
Maven is installed on the Jenkins agent
nopCommerce running locally using docker

Jenkins Pipeline Setup
1. Create a new Jenkins Pipeline job
2. Point it to this repository
3. Jenkins will use the Jenkinsfile at the root of the project
4. Configure a webhook or set a polling schedule under "Build Triggers."

**Key Learnings**
Built and configured a Jenkins CI/CD pipeline from scratch
Connected automated tests to a real pipeline so they run on every commit
Used Page Object Model (POM) to keep test code maintainable
Practiced the professional QA workflow: commit → build → test → report   
