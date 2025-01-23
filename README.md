# MLOps Loan Prediction Model Deployment

This repository contains the code and configuration for the deployment of a machine learning model to predict loan approval based on applicant data. The model is deployed using Flask API and hosted on Reder Cloud for scalability and ease of use.

## Project Overview

In this project, we use a dataset containing information about applicants (e.g., gender, marital status, income, loan amount, etc.) to predict whether a loan will be approved. The machine learning model is trained, serialized, and exposed via a Flask API. The deployment pipeline is automated using GitHub Actions and hosted on Reder Cloud.

## Features

- **Loan Prediction Model**: A machine learning model trained on a dataset of loan applications to predict approval status.
- **Flask API**: A lightweight API built using Flask to serve the model and handle prediction requests.
- **Deployment**: Model deployed on Reder Cloud for easy scaling and monitoring.
- **CI/CD Pipeline**: Continuous Integration and Continuous Deployment (CI/CD) automated via GitHub Actions.
- **Containerization**: Docker container for consistent deployment across environments.

## Prerequisites

Before you begin, make sure you have the following installed:

- Python 3.6+
- Flask
- scikit-learn (for machine learning)
- Git
- Docker (for containerization, if using)
- Reder Cloud (or your cloud platform of choice)

You may also need a GitHub account and permissions to configure GitHub Actions if you're automating the deployment process.

## Live Application
- You can access the live loan prediction application here: https://loan-prediction-application.onrender.com/

