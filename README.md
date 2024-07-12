# Expert Spoon Microservices

This project demonstrates the conversion of a monolithic architecture to a microservices architecture for an online household products order application. The goal is to showcase the benefits of microservices, such as reduced tight coupling, improved scalability, and easier maintenance.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)


## Introduction
The Expert Spoon Microservices project aims to manage various functionalities of an online store, including product listings, user authentication, shopping cart management, and order processing. By leveraging a microservices architecture, each service is responsible for specific tasks, resulting in a more modular and scalable system.

## Features
- User Sign Up and Sign In
- Profile Management
- Product Listings and Details
- Shopping Cart and Wishlist
- Order Creation and Viewing
- Address Management
- Real-time Operations

## Architecture
The project follows a microservices architecture with the following key components:
- **Customer Service**: Manages user authentication and profile-related operations.
- **Product Service**: Handles product listings, details, and management.
- **Shopping Service**: Manages shopping cart, wishlist, and order processing.

Each service is deployed independently and communicates via well-defined APIs. The architecture also includes a gateway for routing requests to the appropriate service.

## Tech Stack
- **NodeJS**: Server-side JavaScript runtime
- **ExpressJS**: Web framework for NodeJS
- **MongoDB**: NoSQL database
- **Docker**: Containerization
- **Nginx**: Web server and reverse proxy
- **JWT (JSON Web Tokens)**: Authentication
- **Redis**: In-memory data structure store (optional, for caching and session management)
- **Microservices Architecture**: Decomposed services for handling different aspects (e.g., customer, product, shopping services)
- **Layered Architecture Pattern**: Clear separation of API, service, and repository layers
- **Gateway Directory**: For request routing and handling
- **.env Configuration**: Environment-specific configurations

