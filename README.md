# Azure CI/CD Web App Deployment (GitHub Actions)

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline deployment of a Node.js web application to Azure App Service using GitHub Actions.

The application is automatically built and deployed whenever changes are pushed to the main branch.

---

## 🏗 Architecture

GitHub Repository  
        ↓  
GitHub Actions (CI/CD Workflow)  
        ↓  
Azure App Service (Linux - Node 20 LTS)  
        ↓  
Public Web Application  

---

## ⚙️ Technologies Used

- Microsoft Azure App Service
- GitHub Actions
- Node.js (Express)
- Linux App Service Plan
- Continuous Integration & Continuous Deployment (CI/CD)

---

## 🚀 Implementation Steps

1. Created Azure App Service (Linux, Node 20 LTS)
2. Connected GitHub repository via Deployment Center
3. Automatically generated GitHub Actions workflow
4. Added Node.js application (`index.js`, `package.json`)
5. GitHub Actions built and deployed app automatically
6. Verified successful deployment via public URL

---

## 🔄 CI/CD Workflow

On every push to `main` branch:

- GitHub Actions triggers
- Node.js app builds
- Deployment to Azure App Service occurs automatically
- Application updates live without manual SSH or intervention

---

## 📸 Screenshots

All deployment and validation screenshots are available in the `/screenshots` directory.

---

## 🎯 Key Learnings

- Configuring Azure App Service
- Connecting GitHub to Azure
- Understanding GitHub Actions workflows
- Debugging failed CI/CD pipelines
- Automating deployments
- Modern DevOps practices

---

## 🌍 Live Application

Deployed to:
https://<your-app-name>.azurewebsites.net

---

## 🚀 Future Enhancements

- Add staging slot
- Implement automated testing in pipeline
- Add environment variables and secrets
- Deploy using Infrastructure as Code (Terraform)
