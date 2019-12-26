FROM openjdk:13-alpine

COPY target/gateway-app-*.jar /opt/gateway-app.jar

CMD ["java", "-jar", "-Dspring.profiles.active=default", "/opt/gateway-app.jar"]