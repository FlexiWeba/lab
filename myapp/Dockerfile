FROM ubuntu:24.04

WORKDIR /app

COPY greet .
# Install packages
RUN apt-get update && apt-get install -y curl ca-certificates 

# Create directories
RUN mkdir -p /app/data

# Download files
RUN curl -o /app/file.txt https://example.com/file.txt


CMD ["./greet"]

