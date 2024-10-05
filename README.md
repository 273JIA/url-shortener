URL Shortener - Full Stack Application (Vue, Spring Boot, Spring Cloud Alibaba, Redis, Sentinel)
Overview

This project is a full-stack URL Shortener application that allows users to generate and manage shortened URLs efficiently. The application is built using Vue.js for the frontend and Spring Boot with Spring Cloud Alibaba for the backend. The architecture ensures scalability and performance through various technologies, including Redis for caching and Sentinel for service stability.
Key Features

    URL Shortening: Generate shortened URLs easily and manage existing links.
    User-Friendly Interface: A responsive and intuitive UI built with Vue.js.
    Backend API Services: RESTful APIs for URL shortening and management using Spring Boot.
    Database Sharding: Utilizes ShardingSphere for database sharding, allowing the application to handle large datasets and ensuring scalability.
    Caching: Redis is employed to cache URL statistics, which reduces the database load and improves response times.
    System Stability: Sentinel is integrated for traffic management, providing QPS throttling and degradation strategies during high loads.

Technologies Used

    Frontend:
        Vue.js: Progressive JavaScript framework for building user interfaces.
    Backend:
        Spring Boot: Framework for building backend services.
        Spring Cloud Alibaba: Provides microservices features, such as service discovery and configuration management.
        ShardingSphere: Database sharding framework to manage large datasets.
    Caching and Monitoring:
        Redis: In-memory data structure store for caching URL statistics.
        Sentinel: Provides monitoring and traffic control for Spring Cloud applications.
