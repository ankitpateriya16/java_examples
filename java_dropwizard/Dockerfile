FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/java_dropwizard-1.0-SNAPSHOT-jar-with-dependencies.jar dropwizard.jar
EXPOSE 8084
ENTRYPOINT ["java", "-jar", "dropwizard.jar"]
