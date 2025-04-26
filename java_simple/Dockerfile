FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/java_simple-1.0-SNAPSHOT-jar-with-dependencies.jar hellodemo.jar
EXPOSE 8089
ENTRYPOINT ["java", "-jar", "hellodemo.jar"]
