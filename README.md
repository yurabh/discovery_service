                                                 discovery_service
1)About the project.

This project is a microservice evreka server in which all other microservices (instances) are registered

2)Start the project locally.

2.1 Required to install the project.

Java 11

2.2 How to run project.

You should create environmental variables that are defined in the resources package like:

application.properties.
2.2.1 For application.properties you should set the value like:

* server.port=${Value}
* eureka.client.register-with-eureka=${Value}
* eureka.client.fetch-register=${Value}
* spring.zipkin.base-url=${Value}
* spring.sleuth.sampler.probability=${Value}
