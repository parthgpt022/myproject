# FinTech Lab – Lab 1 & 2  
## Deployment of Java Application on Microsoft Azure

### Student Details
- Name: Parth Gupta  
- GitHub Username: parthgpt022  
- Course/Lab: FinTech Lab  
- Lab Number: Lab 1  

---

## Objective
The objective of this lab is to deploy a Java-based Spring Boot application to Microsoft Azure App Service using Maven and GitHub, and make the application publicly accessible via a cloud URL.

---

## Technologies Used
- Java 17  
- Spring Boot  
- Apache Maven  
- Git & GitHub  
- Microsoft Azure App Service  
- Azure Web App Maven Plugin  

---

## Project Description
A simple Spring Boot web application was created and packaged as a JAR file using Maven. The application was then deployed to Microsoft Azure App Service using the Azure Web App Maven Plugin. The deployment process involved configuring Azure resources such as Resource Group, App Service Plan, and Web App.

---

## Steps Performed

### 1. Project Setup
- Created a Spring Boot project using Maven.
- Configured Java version to 17 in `pom.xml`.

### 2. Version Control
- Initialized a Git repository.
- Pushed project source code to GitHub.

### 3. Azure Configuration
- Logged into Azure using Azure Cloud Shell.
- Used Azure for Students subscription.
- Configured Azure Web App using Maven plugin with:
  - OS: Linux
  - Java Version: 17
  - Pricing Tier: F1 (Free)
  - Region: Central India

### 4. Deployment
- Built the project using Maven.
- Deployed the application using: mvn com.microsoft.azure:azure-webapp-maven-plugin:2.13.0:deploy
- Azure resources were created automatically.
- Application was deployed successfully.

### 5. Verification
- Verified successful deployment via Azure portal.
- Accessed the application using the public Azure URL.

---

## Azure Application URL: https://myproject-1768403926784.azurewebsites.net

---

## Result
The Java Spring Boot application was successfully deployed and is running on Microsoft Azure App Service. The deployment process was completed without errors, and the application is accessible through a public URL.

---

## Conclusion
This lab demonstrated how cloud platforms like Microsoft Azure can be used to deploy and manage Java applications efficiently. The integration of Maven, GitHub, and Azure simplifies deployment and improves scalability and accessibility.

---

## Submission
- GitHub repository contains complete source code and deployment configuration.
- README file documents the full deployment process.
