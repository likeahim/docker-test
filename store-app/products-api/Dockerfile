FROM openjdk

WORKDIR usr/src/app

EXPOSE 8080

ARG JAR_FILE

COPY ${JAR_FILE} app.jar

CMD ["java", "-jar", "app.jar"]