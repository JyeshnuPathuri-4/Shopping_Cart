# Use an official Java runtime as a parent image
FROM openjdk:17-jre-slim

# Set the working directory in the container
WORKDIR /Shopping_Cart

# Copy the compiled JAR file from the target directory to the working directory
# Dockerfile in resources folder
COPY ../target/Shopping_Cart-0.0.1-SNAPSHOT.jar Shopping_Cart.jar

# Expose the application port
EXPOSE 8081

# Run the application
ENTRYPOINT ["java", "-jar", "Shopping_Cart.jar"]
