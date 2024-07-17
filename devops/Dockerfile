FROM openjdk:17.0.2-slim

COPY ./build/libs/*.jar ./stalkServiceDiscovery.jar

ENTRYPOINT ["java", "-jar", "./stalkServiceDiscovery.jar"]
