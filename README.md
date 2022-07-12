# Discovery Server

The Discovery server  allows clients applications to find services through a router or a load balancer,
It provides also a dashboard where there are displayed all the services registered and it is accessible from the following link:

* http://localhost:8080/eureka/microservices

The discovery server is only accessible through api gateway

# Setup

The project is strictly connected with its parent project "Spring-SalaryCalculator-Microservices",
Please make sure to clone the parent repository.

* Required:
    * Docker


* To create a container in Docker, follow the below instructions:

    * Go to the folder: Spring-SalaryCalculator-Microservices
    * Create a jar file running "gradle build" or "gradle bootJar"
    * execute: docker-compose -f docker-compose.yml up
    
