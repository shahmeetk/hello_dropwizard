FROM openjdk:8-jdk

COPY example.yaml /data/dropwizard-sample/example.yaml
COPY /target/hello-dropwizard-1.0-SNAPSHOT.jar /data/dropwizard-sample/hello-dropwizard-1.0-SNAPSHOT.jar

WORKDIR /data/dropwizard-sample


ENTRYPOINT ["java","-jar","hello-dropwizard-1.0-SNAPSHOT.jar","server","example.yaml"]

EXPOSE 8080
EXPOSE 8081