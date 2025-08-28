FROM ubuntu
RUN apt-get update && \
    apt-get install -y maven git default-jre
WORKDIR /app
COPY . /app
EXPOSE 5000
CMD ["java", "-jar", "target/java-sample-21-1.0.0.jar"]
