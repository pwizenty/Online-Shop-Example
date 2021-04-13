# Online-Shop-Example

This repository contains an online shop example based on the microservice architecture. 
The microservices are implemented in Kotlin using the Spring Framework.

The online shop example consists of the functional microservices ItemService, OrderService, 
and CustomerService, responsible for the items, orders, and customers. The functions of the services 
are offered via the corresponding interfaces.

Besides, infrastructural services are also used. These include service discovery, which implements 
the microservice pattern service registry. The API Gateway Pattern is also used and realized by the API Gateway Service, 
allowing centralized access to the services. MongoDB and MariaDB are used as database systems.

![Online Shop example SOAML diagram.](https://github.com/pwizenty/Online-Shop-Example/blob/master/ordersystem.png?raw=true)
