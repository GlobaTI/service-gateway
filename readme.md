# service-gateway


## Dockerize
Run ```mvn clean package docker:build``` to build the application and generate the docker image for the project.

### Running the Docker image:
```docker run -p {host-port}:8080 --name service-gateway service-gateway```

