FROM docker.io/library/eclipse-temurin:23-jre

WORKDIR /app

COPY us-eureka.war app.war

EXPOSE 8761

ENTRYPOINT ["java", "-jar", "app.war"]