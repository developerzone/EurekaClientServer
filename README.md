# EurekaClientServer
This consists of an Eureka Server and a client.
Open both the applications (myeurekaserver and catalog) separately in Intellij Idea.
Start both the applications. Hit http://localhost:8761/ and see how the client is registering itself to Eureka Server.
Run the client separately at port 8081 by hitting http://localhost:8081/product/list
The client in this example also contains the H2 database with Spring JPA for database Manipulation.
Play with the properties and do add more features to understand the concept better.

