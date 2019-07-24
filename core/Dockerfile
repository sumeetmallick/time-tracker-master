FROM openjdk:8-jdk-alpine
EXPOSE 8080
VOLUME /tmp
ADD time-tracker-core-0.5.0-SNAPSHOT.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/.urandom -jar /app.jar
