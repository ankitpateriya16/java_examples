FROM openjdk:21-jdk-slim
WORKDIR /app
COPY target/java_httpserver-1.0-SNAPSHOT-jar-with-dependencies.jar hellodemo.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "hellodemo.jar"]
