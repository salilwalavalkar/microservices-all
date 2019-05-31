FROM openjdk:8-jdk-alpine
ADD target/sample-client-1.0.jar sample-client.jar
ENTRYPOINT ["java", "-jar", "/sample-client.jar"]
EXPOSE 8081
COPY wait-for.sh /wait-for.sh
RUN chmod +x /wait-for.sh