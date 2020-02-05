FROM openjdk:11-jre
COPY ./target/sample-application-http-api-server-0.0.1-SNAPSHOT-exec.jar ./httpapp.jar

EXPOSE 8080

ENTRYPOINT java -jar httpapp.jar
