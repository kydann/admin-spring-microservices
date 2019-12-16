FROM java:8
MAINTAINER Christian Daniel Sayago Rivero <kydann.2907@gmail.com>
VOLUME /tmp
EXPOSE 8081
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]