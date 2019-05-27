FROM openjdk:8-jdk-alpine
ADD target/edge-service-1.0.jar edge-service.jar
ENTRYPOINT ["java", "-jar", "/edge-service.jar"]
EXPOSE 8761
