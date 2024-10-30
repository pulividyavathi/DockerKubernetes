# DockerKubernetes



# Docker and Kubernetes Web Application Deployment

## Overview

This project demonstrates how to package a web application with a MongoDB database into a Docker container and deploy it on a Kubernetes cluster using Minikube. This setup is ideal for development and testing purposes, allowing you to simulate a production Kubernetes environment on your local machine.

## Prerequisites

- Docker
- Homebrew (for macOS users)
- Basic knowledge of Docker and Kubernetes concepts

## Installation

### 1. Install Docker


. You can download it from the [official Docker website](https://www.docker.com/get-started).

### 2. Install Minikube

For macOS users:

brew install minikube


 . For other operating systems, please refer to the official Minikube documentation.

### 3. Configure Minikube Driver

We'll use Docker as the driver for Minikube. Start Minikube with the Docker driver:

minikube start --driver docker

Usage
Check Minikube Status
To verify the status of Minikube:

minikube status

Check Kubernetes Nodes
Minikube includes kubectl as a dependency. To check the status of all nodes:

kubectl get nodes
