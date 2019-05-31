FROM openjdk:8-jdk-alpine
ADD target/discovery-service-1.0.jar discovery-service.jar
ENTRYPOINT ["java", "-jar", "/discovery-service.jar"]
EXPOSE 8761
COPY wait-for.sh /wait-for.sh
RUN chmod +x /wait-for.sh