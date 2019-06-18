FROM openjdk:11.0.3-jre

ARG JAR_FILE

COPY application-api-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "/usr/apps/app.jar"]

EXPOSE 8080 8090 6379


