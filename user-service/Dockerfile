FROM openjdk:11
ADD target/*.jar app.jar
ENV JAVA_OPTS=''
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar app.jar" ]
