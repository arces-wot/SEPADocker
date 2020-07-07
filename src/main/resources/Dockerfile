FROM openjdk:8-alpine

WORKDIR /

COPY docker.jsap docker.jsap
COPY log4j2.xml log4j2.xml

COPY producer-0-SNAPSHOT-jar-with-dependencies.jar /data/agent.jar

ENTRYPOINT ["java","-jar","agent.jar"]

