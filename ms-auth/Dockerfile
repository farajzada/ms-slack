FROM eclipse-temurin:21-jdk-alpine

ARG JAR_FILE=build/libs/ms-auth-1.0-SNAPSHOT.jar

COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]