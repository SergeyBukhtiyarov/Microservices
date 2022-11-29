FROM openjdk:17-slim
ADD ./target/configserver-0.0.1-SNAPSHOT.jar backendconfig.jar
ENTRYPOINT ["java","-jar", "backendconfig.jar"]