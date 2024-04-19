# Advanced Calculator Microservice
#### Welcome to the Advanced Calculator Microservice repository. This guide provides detailed steps on how to build, deploy, and interact with the Advanced Calculator Microservice using Docker and Kubernetes.

## Prerequisites
#### Before you begin, ensure you have the following installed:
#### Docker
#### Kubernetes (Minikube for local deployment)
#### kubectl command-line tool

## Setup Instructions

#### 1. Clone the Repository
#### git clone https://github.com/s223686707/sit323-737-2024-t1-prac7p.git
#### cd sit323-737-2024-t1-prac7p

#### 2. Build and Push the Docker Image
#### docker build -t calculator-microservice .
#### docker push calculator-microservice

#### 3. Start Minikube
#### minikube start

#### 4. Deploy to Kubernetes
#### kubectl apply -f deployment.yml
#### kubectl apply -f service.yml

#### git clone https://github.com/s223686707/sit323_737-2024-t1-prac4c.git
#### npm install
#### node server.js
