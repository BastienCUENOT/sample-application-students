FROM openjdk:11-jre
ENV MYAPP_HOME $HOME/build/BastienCUENOT/sample-application-students/sample-application-db-changelog-job
WORKDIR $MYAPP_HOME
COPY $MYAPP_HOME/target/*.jar $MYAPP_HOME/myapp.jar

EXPOSE 8080

ENTRYPOINT java -jar myapp.jar
