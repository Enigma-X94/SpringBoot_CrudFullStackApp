FROM eclipse-temurin:11-jdk-jammy
WORKDIR /app
COPY target/springtboot-backend-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
