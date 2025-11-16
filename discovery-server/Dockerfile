FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/*.war discovery-server-0.0.1-SNAPSHOT.war
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "discovery-server-0.0.1-SNAPSHOT.war"]