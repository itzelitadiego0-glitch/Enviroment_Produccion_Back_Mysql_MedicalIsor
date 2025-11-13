FROM eclipse-temurin:21-jdk-alpine
ARG JAR_FILE=target/citasBackend-0.0.1.jar
COPY ${JAR_FILE} citasBackend.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "citasBackend.jar"]