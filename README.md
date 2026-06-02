# CI/CD Pipeline using Azure

## Overview
Automated CI/CD pipeline built with Azure DevOps, 
Azure Container Registry, and Azure App Service.

## Architecture
- **App**: Python Flask web application
- **CI/CD**: Azure Pipelines
- **Container Registry**: Azure Container Registry (ACR)
- **Deployment**: Azure App Service (Linux container)

## Pipeline Flow
1. Push code to GitHub
2. Azure Pipelines triggers automatically
3. Docker image is built
4. Image pushed to ACR
5. App deployed to Azure App Service

## Technologies Used
- Python / Flask
- Docker
- Azure DevOps Pipelines
- Azure Container Registry
- Azure App Service
- GitHub