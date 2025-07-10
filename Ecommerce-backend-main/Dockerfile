# Use official OpenJDK image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy all files
COPY . .

# Build the project using Maven Wrapper (skipping tests)
RUN ./mvnw clean package -DskipTests

# Expose the port
EXPOSE 8080

# Run the JAR file dynamically
CMD sh -c "java -jar target/*.jar"
