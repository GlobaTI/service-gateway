FROM openjdk:8-jre-alpine
ADD service-gateway-0.0.1-SNAPSHOT.jar service-gateway.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/service-gateway.jar"]
