# Demos

Welcome to the **Demos** section! Here, you can find a collection of projects showcasing various technologies and architectures for your reference. Whether you are interested in REST Microservices or Asynchronous-Microservices, these projects are designed to demonstrate the power and flexibility of modern development frameworks.

## REST Microservices

This set of projects utilizes **Spring Boot**, **MySQL**, **Docker**, and **Kubernetes** to build efficient and scalable microservices. Check out the individual repositories below:

1. [ConfigServer](https://github.com/dmanias/ConfigServer): A central configuration service that enables dynamic updates for microservices.

2. [PaymentService](https://github.com/dmanias/PaymentService): A microservice handling payment-related functionalities.

3. [ProductService](https://github.com/dmanias/ProductService): A microservice managing product-related operations.

4. [OrderService](https://github.com/dmanias/OrderService): A microservice responsible for order processing, with extended testing.

5. [ms-initial-setup](https://github.com/dmanias/ms-initial-setup): A starter project to quickly set up new microservices.

6. [microdemo-spring-configuration](https://github.com/dmanias/microdemo-spring-configuration): A demonstration of Spring configuration in microservices.

## Asynchronous Microservices

In this real-world example, we explore a multi-module Maven project where a producer fetches messages from Wikimedia and sends them to Kafka. The consumer then processes these messages and stores them in MySQL. This project is built using **Spring Boot**, **MySQL**, and **Kafka**.

Check it out: [Asynchronous-Microservices](https://github.com/dmanias/Asynchronous-Microservices)

Feel free to explore the repositories, experiment with the code, and learn from the examples provided. If you have any questions or feedback, don't hesitate to reach out. Happy coding!

## gRPC Spring Boot Multimodule Maven Demo with Elasticsearch Integration

Explore the power of gRPC with Spring Boot in this demo project, now enhanced with the addition of Elasticsearch for logging and data analysis. gRPC is a high-performance, open-source framework developed by Google. The main advantage of gRPC is that it uses protocol buffers by default as its message format.

With the latest addition of Elasticsearch, a powerful, open-source distributed search and analytics engine, the demo is now able to log each gRPC request. This provides valuable insights into the usage of your gRPC services, making it a powerful tool for debugging and monitoring.

Check it out: [gRPC Demo](https://github.com/dmanias/grpcDemo)

## Golang Demo

This is a log audit service built in Golang. The service aggregates events and allows users to run queries on them. Events are indexed by their invariant parts, and the variant parts are stored together under the name "data." The events endpoints are protected with bearer token authentication. In the store event procedure, if the data fails to be stored in the database, it is stored in a temporary storage.
This project is built using **Golang**, **MongoDB**, **Mongo Express**, **Mongo Express**, **Docker**, **Docker Compose**, **Swagger**, **Prometheus**.


Check it out: [Golang Logs Audit Demo](https://github.com/dmanias/logs-audit)

Feel free to explore the repositories, experiment with the code, and learn from the examples provided. If you have any questions or feedback, don't hesitate to reach out. Happy coding!
