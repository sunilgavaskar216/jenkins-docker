FROM openjdk:17
EXPOSE 8080
#COPY target/docker-jenkins-integration.jar docker-jenkins-integration.jar
COPY target/*.jar docker-jenkins-integration.jar

ENTRYPOINT ["java","-jar","/docker-jenkins-integration.jar"]