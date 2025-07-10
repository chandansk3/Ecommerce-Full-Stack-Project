# Use official OpenJDK image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy project files
COPY . .

# Give execute permission to Maven Wrapper
RUN chmod +x ./mvnw

# Build the project (skipping tests)
RUN ./mvnw clean package -DskipTests

# Expose backend port
EXPOSE 8080

# Run the JAR file
CMD sh -c "java -jar target/*.jar"
