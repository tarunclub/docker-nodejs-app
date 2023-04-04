# Docker-nodejs-app

This repository contains a basic Node.js application that can be run in a Docker container. The Docker image is published on [Docker Hub](https://hub.docker.com/r/tarunclub/hey-nodejs).

## Running the application

### Prerequisites

To run the application, you will need to have [Docker](https://www.docker.com/) installed on your system.

### Running the Docker image

You can run the Docker image using the following command:

```
docker run -p 8000:8000 tarunclub/hey-nodejs
```


This will start the Node.js application inside a Docker container and expose it on port 8000.

### Accessing the application

You can access the application by opening your web browser and navigating to [http://localhost:8000](http://localhost:8000). You should see a "Hey Node.js!" message displayed in your browser.

## Building the Docker image

If you want to build the Docker image yourself, you can use the following command:

```
docker build -t hey-nodejs .
```


This will build the Docker image using the Dockerfile in the repository.

## Contributing

If you find any issues with the application or want to contribute to it, feel free to create a pull request or open an issue in the repository.


