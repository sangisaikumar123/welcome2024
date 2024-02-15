FROM openjdk:17
EXPOSE 8024
ADD target/welcome-1.0.0.jar welcome.jar
ENTRYPOINT exec java -Dserver.port=8024 -jar welcome.jar
