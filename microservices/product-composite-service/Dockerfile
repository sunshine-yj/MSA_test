FROM eclipse-temurin:21-jre-noble
WORKDIR /application
COPY build/libs/*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]