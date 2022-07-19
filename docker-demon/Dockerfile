FROM java:8
EXPOSE 8081
ADD target/docker-demo.jar docker-demon.jar
ENTRYPOINT ["java","-jar","docker-demon.jar"]