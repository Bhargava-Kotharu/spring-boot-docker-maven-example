# Spring Boot Docker Maven Example #

## Spring boot application ##

We have created a simple spring boot applicaiton and exposed an endpoint.

## Building Docker Image ##

 mvn package dockerfile:build

## Check Docker Image ##

To see the newly created docker image, run command - docker image ls 

## Running Docker Image ##

### Running in the same window ###

docker run -p 5000:8080 spring-boot-docker-example

### Running as a background process ###

docker run -d -p 8080:8080 spring-boot-docker-example


