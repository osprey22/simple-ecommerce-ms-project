FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} catalog-service.jar
ENTRYPOINT ["java","-jar","/catalog-service.jar"]
EXPOSE 8101