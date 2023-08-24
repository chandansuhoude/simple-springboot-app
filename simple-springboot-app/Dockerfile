FROM openjdk:8-jdk-alpine
RUN mkdir -p /opt/app
WORKDIR /opt/app
COPY target/*.jar /app.jar
EXPOSE 9090
CMD ["java", "-jar", "app.jar"]
~                              
