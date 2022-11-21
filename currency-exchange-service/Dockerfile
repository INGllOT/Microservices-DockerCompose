FROM openjdk:17
ARG JAR_FILE=target/currency-exchange-service-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8000
ENTRYPOINT ["java", "-jar", "/app.jar"]
