FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/*.war api-gateway-0.0.1-SNAPSHOT.war
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "api-gateway-0.0.1-SNAPSHOT.war"]