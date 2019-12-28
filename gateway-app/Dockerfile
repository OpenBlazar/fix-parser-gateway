FROM openjdk:13-alpine

ARG VERSION=*

COPY target/gateway-app-${VERSION}.jar /opt/gateway-app.jar

CMD ["java", "-jar", "-Dspring.profiles.active=default", "/opt/gateway-app.jar"]