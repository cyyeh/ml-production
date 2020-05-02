# Deployment of Machine Learning Models

## Introduction

![](https://i.imgur.com/wfesLri.png)

### Sections Overview

- Machine Learning - Research Environment
    - Data gathering
    - Feature engineering
    - Feature selection
    - Machine learning model building
    - Model assessment
- Machine Learning - System Architecture
    - What is it and why it is important
    - Challenges of creating a suitable system architecture
    - Different architecture approaches
    - Architecture components
- Building a reproducible ML pipeline
    - Different ways utilized in the industry
    - Procedural programming
    - OOP with a custom pipeline
    - OOP with third party pipeline
    - Pros and cons of each method
    - Our recommendation
    - Should we integrate feature selection into the production pipeline?
- Course Setup and Key Tools
    - Git
    - System path and python path
    - Virtual environments
- Machine Learning Pipeline Application
    - Train the model and make predictions
    - Ensuring data format - data validation
    - Versioning and logging
    - Building a python package with the model
- Serving the Model via REST API
    - Introduction to Flask
    - Creating the API skeleton
    - Versioning and Logging
    - Schema validation
- Continuous Integration and Deployment Pipelines
    - Introduction to CI/CD
    - CircleCI
    - Publishing the model to Gemfury
    - Testing the CI pipeline
- Differential Testing
    - Setting up differential tests
    - Differential testing in CI
- Deploying to a PaaS(Heroku)
    - What is a PaaS?
    - Utilizing Heroku
    - Testing the deployment manually
    - Deployment to Heroku using CI
- Running Apps with Containers(Docker)
    - Intro to containers and Docker
    - Installing docker
    - Creating an API App Dockerfile
    - Building and Running a Docker Container
    - Releasing to Heroku utilizing Docker
- Deploying to an IaaS(AWS)
    - Intro to AWS
    - Creating an AWS account
    - Installing and Configuring the AWS CLI
    - Elastic Container Registry
    - Elastic Container Service
    - Deploying to ECS using CI
- Deploying with Big Data - Deep Learning
    - Classify images with CNN
    - Challenges of deploying models using big data
    - Updating applications to big data
    - AWS S3 for large datasets
- Common Issues Found During Deployment