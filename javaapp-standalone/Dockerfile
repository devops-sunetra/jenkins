FROM ubuntu
RUN apt-get update && apt-get install maven git default-jre -y
WORKDIR /app
RUN git clone https://github.com/Vandu0409/jenkins.git && cd jenkins/javaapp-standalone && mvn clean package
EXPOSE 5000
CMD ["java", "-jar", "/app/jenkins/javaapp-standalone/target/java-sample-21-1.0.0.jar"]
