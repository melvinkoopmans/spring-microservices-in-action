FROM java:8

# Add Maven dependencies
ADD ./target/lib /lib

# Add the service
ADD ./target/organizations-1.0-SNAPSHOT.jar /app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]