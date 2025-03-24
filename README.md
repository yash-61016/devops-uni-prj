# E-commerce Platform - DevOps Module Project

## Overview

This repository serves as the central hub for the **E-commerce Platform** project, developed as part of the **DevOps module** for my university coursework. The project demonstrates the application of modern DevOps practices and technology choices in building a scalable, secure, and maintainable E-commerce platform using a microservices architecture.

## Project Description

The E-commerce platform is built using Vue.js for the frontend, .NET 7 Minimal API for the backend microservices, and PostgreSQL for data storage. The system implements OAuth 2.0 with Auth0 for authentication and uses Azure Service Bus for communication between microservices. All components are deployed on Azure Cloud services.

## Related Repositories

This project is divided into multiple repositories to reflect its microservices architecture:

1. [BFF (Backend For Frontend)](https://github.com/yash-61016/devops_bff)
   - API gateway service that handles communication between the frontend and backend microservices

2. [Webclient](https://github.com/yash-61016/devops_webclient)
   - Vue.js frontend application with TypeScript and Tailwind CSS

3. [Card Service](https://github.com/yash-61016/devops_cart_service)
   - Microservice for handling payment card operations and processing

4. [Sale Order Service](https://github.com/yash-61016/devops_sale_order_service)
   - Microservice for managing customer orders and order processing

## Technology Stack

### Frontend
- **Framework**: Vue.js with TypeScript
- **Styling**: Tailwind CSS
- **Deployment**: Azure Static Web App

### Backend
- **API**: .NET 7 Minimal API
- **Database**: PostgreSQL
- **Hosting**: Azure Web API
- **Database Service**: Azure Database for PostgreSQL

### Communication & Integration
- **Microservices Communication**: Azure Service Bus
- **Authentication**: OAuth 2.0 with Auth0

### C4 Diagram
![oveview](https://github.com/user-attachments/assets/005638ba-fa47-40fa-beeb-e056bf2b033c)

![overview2](https://github.com/user-attachments/assets/cfab3e1c-547d-4369-8b22-2fc259968fe5)

## DevOps Practices Implemented

As part of the university DevOps module, this project implements:

1. **Continuous Integration (CI)** - Automated builds and tests
2. **Continuous Deployment (CD)** - Automated deployment to Azure
3. **Microservices Architecture** - Independent, scalable services
4. **Automated Testing** - Unit and integration tests

## Challenges & Learnings

The project involved transitioning from PHP/Python development to .NET 7, implementing event-based architecture with Azure Service Bus, and managing microservices communication. Given more time, I would explore alternatives like Azure Event Grid or RabbitMQ for messaging between services.


## Acknowledgment

This project was developed as part of my coursework for the **DevOps module** at my university, demonstrating practical application of DevOps principles in a real-world scenario.

---
