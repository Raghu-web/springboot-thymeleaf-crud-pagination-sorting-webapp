FROM eclipse-temurin:17-jre-jammy

WORKDIR /opt

COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
