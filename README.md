# starter-micro-services


## How to install it and use it:

You need to have installed java 1.8 and Gradle


## How to run the different microservices independently

1.- run config-server --> bootRun  --> it will be started on port 9000 <br />
2.- run eureka-server --> bootRun  --> it will be started on port 8761 <br />
3.- run guest-service --> bootRun  --> it will be started on port 8102 <br />
4.- run reservation-business-service --> bootRun  --> it will be started on port 8500 <br />
5.- run reservation-server --> bootRun  --> it will be started on port 8103 <br />
6.- run reservation-web --> bootRun  --> it will be started on port 8600 <br />
6.- run room-service --> bootRun  --> it will be started on port 8101 <br />

Then type in your browser http://localhost:8600/reservations

## Technologies used:

-Java 8

-Spring Boot

-Spring Core

-Gradle build tool

-Spring MVC

-H2 database (Database in memory)








