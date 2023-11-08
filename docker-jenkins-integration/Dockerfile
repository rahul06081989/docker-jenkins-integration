FROM openjdk:8
EXPOSE 8080
ADD target/docker-jenkins-integration.jar  dockerjenkinsintegration
ENTRYPOINT ["java","-jar", "/docker-jenkins-integration.jar"]