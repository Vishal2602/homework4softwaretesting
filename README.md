# Flask Docker Application

A simple Flask "Hello World" application containerized with Docker.

## Components

- Flask web application
- Docker container configuration

## Setup Instructions

1. Build the Docker image:
   ```
   docker build -t flask-docker .
   ```

2. Run the Docker container:
   ```
   docker run -p 5001:5000 flask-docker
   ```

3. Access the application at:
   ```
   http://localhost:5001
   ``` 