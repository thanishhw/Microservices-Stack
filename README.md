# Microservices-Stack

Production Microservices Stack

1. API Gateway
Single entry point for all client requests. Handles routing, filtering, and load balancing.

2. Service Registry
Directory of all available services. Gateway uses this for service discovery. Examples: Consul, Eureka, Zookeeper.

3. Service Layer
Individual microservices handling specific business functions.

4. Authorization Server
Secures microservices and manages access control.

5. Data Storage
Application databases.

6. Distributed Caching
Improves performance through caching layers.

7. Async Communication
Message queues enable asynchronous service communication.

8. Metrics Visualization
Services publish metrics to Prometheus, visualized through Grafana dashboards.

9. Log Aggregation
Centralized logging using ELK stack.
