FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/*.war order-service-0.0.1-SNAPSHOT.war
EXPOSE 8082
ENTRYPOINT ["java", "-jar", "order-service-0.0.1-SNAPSHOT.war"]