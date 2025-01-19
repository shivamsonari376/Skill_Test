# Skill_Test

# Microservices Application

## Description
This project contains four Node.js microservices:
1. User Service (Port 3000)
2. Product Service (Port 3001)
3. Order Service (Port 3002)
4. Gateway Service (Port 3003)

## Prerequisites to be installed on EC2 Instances
- Docker
- Docker Compose

## Setup Instructions
1. Clone the repository:
  
   git clone https://github.com/mohanDevOps-arch/Microservices-Task.git
   cd Microservices-Task/Microservices
Create Dockerfiles for Each Service
Create Dockerfile for each service in their respective folders. Below are examples:

User Service (user-service/Dockerfile)
Product Service (product-service/Dockerfile)
Order Service (order-service/Dockerfile)
Gateway Service (gateway-service/Dockerfile)

Create Docker Compose Configuration
In the Microservices folder, create a docker-compose.yml file



Build and Start the Application
Run the following commands to build and start all services:
docker-compose up --build -d
docker ps -a
