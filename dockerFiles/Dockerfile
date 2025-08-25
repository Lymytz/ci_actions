# todo nom d'image à variabiliser
FROM eclipse-temurin:21
LABEL authors="Yves"
ENV JAVA_HOME=/opt/java/openjdk

WORKDIR ./

COPY ./*.jar app.jar


ENTRYPOINT ["java", "-Dspring.profiles.active=dev", "-jar", "app.jar"]
