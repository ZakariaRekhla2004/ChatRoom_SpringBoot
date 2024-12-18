# Use an official OpenJDK image as the base image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the Spring Boot application jar to the container
COPY target/spring_chatroom_app-0.0.1-SNAPSHOT.jar app.jar

# Expose the application's default port
EXPOSE 8080

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "app.jar"]
