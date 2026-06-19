# CI/CD Pipeline for ML Model using GitHub Actions

An automated CI/CD pipeline that runs tests and validates an ML model on every code push, reducing manual effort in the deployment process.

## Tech Stack
Python, GitHub Actions, Pytest, YAML, Shell Scripting

## Features
- Automated CI/CD pipeline triggered on every push to the repository
- Unit testing of ML pipeline code using Pytest
- Automated model validation before deployment
- YAML-based workflow configuration for GitHub Actions

## How It Works
1. Code is pushed to the GitHub repository
2. GitHub Actions workflow is triggered automatically
3. Unit tests run using Pytest to validate code correctness
4. On success, the pipeline proceeds to model validation and deployment steps

## Future Improvements
- Add deployment to cloud platform (AWS/Azure)
- Integrate model performance checks before deployment
