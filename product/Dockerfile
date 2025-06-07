FROM openjdk:17
VOLUME /tmp
COPY target/product-service.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]