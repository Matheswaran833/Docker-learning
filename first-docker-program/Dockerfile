# Use the official Java image
FROM openjdk:17

# Set working directory inside the container
WORKDIR /app

# Copy the Java file into the container
COPY Main.java .

# Compile the Java file
RUN javac Main.java

# Run the program
CMD ["java", "Main"]
