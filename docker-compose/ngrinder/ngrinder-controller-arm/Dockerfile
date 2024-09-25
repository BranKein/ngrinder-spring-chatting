FROM azul/zulu-openjdk:11

ARG WAR_FILE=./*war
COPY ${WAR_FILE} app.war

ENTRYPOINT ["java", "-jar", "/app.war"]
