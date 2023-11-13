FROM openjdk:8
COPY ./spark-lms-0.0.1-SNAPSHOT.jar /dockerimages/
ENTRYPOINT exec java -jar /dockerimages/spark-lms-0.0.1-SNAPSHOT.jar
EXPOSE 8080