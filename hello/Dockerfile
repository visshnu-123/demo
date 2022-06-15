FROM adoptopenjdk/openjdk11:alpine-jre
ADD build/libs/helloms-0.0.1-SNAPSHOT.js helloms.jar
ENTRYPOINT ["java","-jar","helloms.jar"]