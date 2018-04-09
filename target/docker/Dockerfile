FROM java:latest

ADD target/*.jar app.jar

RUN bash -c 'touch /app.jar'

ENTRYPOINT["java","-jar","/app.jar"]