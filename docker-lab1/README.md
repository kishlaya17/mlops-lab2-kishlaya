# Docker Lab 1 – Machine Learning Model Training

## Overview
This project demonstrates how to containerize a simple machine learning training workflow using Docker.
The application trains a Random Forest classifier on the Iris dataset and saves the trained model.

## Modifications Made
- Used Python 3.10 slim base image
- Installed dependencies using requirements.txt
- Added environment variable for model identification
- Included .dockerignore for clean Docker builds

## Build the Docker Image
```bash
docker build -t lab1:v1 .
