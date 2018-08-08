FROM cargo.caicloudprivatetest.com/library/java:8

COPY demohelloworld.jar  /usr/src/myapp/

WORKDIR /usr/src/myapp/
RUN ls /usr/src/myapp
ENTRYPOINT java -jar demohelloworld.jar
EXPOSE 8080
