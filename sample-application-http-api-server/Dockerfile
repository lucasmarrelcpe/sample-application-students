FROM openjdk:11-jdk
ENV MY_HOME /opt/myapp
WORKDIR $MY_HOME
COPY ./target/*-exec.jar $MY_HOME/myapp.jar
ENTRYPOINT ["java","-jar","myapp.jar"]
