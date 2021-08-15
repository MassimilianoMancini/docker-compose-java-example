FROM openjdk:11

COPY /target/*-jar-with-dependencies.jar /app/app.jar

CMD ["java", "-jar", "/app/app.jar", "mongodb"]