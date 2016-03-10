# Dockerized Swagger UI

This is a docker container that builds the Swagger UI webapp and nginx. The image is kept as small as possible.

## Setup and Installation

### Clone repo and submodules

    $> git clone https://github.com/walterscarborough/docker-swagger-ui.git

### Setup config files

There are no configuration files that need to be changed to deploy this container.

### Building the docker container

    $> cd docker-swagger-ui

    $> docker build -t swagger-ui .

### Running the docker container

    $> docker run -it swagger-ui
