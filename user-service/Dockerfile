FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/*.war user-service-0.0.1-SNAPSHOT.war
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "user-service-0.0.1-SNAPSHOT.war"]