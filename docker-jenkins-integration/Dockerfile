FROM openjdk:8
EXPOSE 8080
ADD target/docker-jenkins-integraion.jar docker-jenkins-integraion.jar
ENTRYPOINT ["java","-jar", "/docker-jenkins-integration.jar"]