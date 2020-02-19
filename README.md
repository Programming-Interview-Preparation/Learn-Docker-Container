# Learn Docker Container

### Docker - Overview

- Docker is a container management service.
- The keywords of Docker are develop, ship and run anywhere.
- The whole idea of Docker is for developers to easily develop applications, ship them into containers which can then be deployed anywhere.

- Initial release of Docker was in March 2013


### Features of Docker

- Easy and Faster Configuration
- Increase productivity
- Application Isolation
- Routing Mesh
- Security Management


### Components of Docker

Docker has the following components

- Docker for Mac − It allows one to run Docker containers on the Mac OS.
- Docker for Linux − It allows one to run Docker containers on the Linux OS.
- Docker for Windows − It allows one to run Docker containers on the Windows OS.
- Docker Engine − It is used for building Docker images and creating Docker containers.
- Docker Hub − This is the registry which is used to host various Docker images.
- Docker Compose − This is used to define applications using multiple Docker containers.

### Docker Architecture

1. Client: Docker provides Command Line Interface (CLI) tools to client to interact with Docker daemon. Client can build, run and stop application. Client can also interact to Docker_Host remotely.
2. Docker_Host: It contains Containers, Images, and Docker daemon. It provides complete environment to execute and run your application.
3. Registry: It is global repository of images. You can access and use these images to run your application in Docker environment.

The Docker daemon: It is a process which is used to listen for Docker API requests. It also manages Docker objects like: images, container, network etc. A daemon can also communicate with other daemons to manage Docker services.

The Docker client: The Docker client is the primary way that many Docker users interact with Docker. When we use commands such as docker run, the client sends these commands to docker d, which carries them out. The docker command uses the Docker API.

Docker Registries: Docker registry is used to store Docker images. Docker provides the Docker Hub and the Docker Cloud which are public registries that anyone can use. Docker is configured to look for images on Docker Hub by default.

When we use the docker pull or docker run commands, the required images are pulled from your configured registry. When you use the docker push command, your image is pushed to your configured registry.

### Docker Installation

- Discuss Next

### Docker Container and Image

Docker container is a running instance of an image. You can use Command Line Interface (CLI) commands to run, start, stop, move, or delete a container. You can also provide configuration for the network and environment variables. Docker container is an isolated and secure application platform, but it can share and access to resources running in a different host or container.

An image is a read-only template with instructions for creating a Docker container. A docker image is described in text file called a Dockerfile, which has a simple, well-defined syntax. An image does not have states and never changes. Docker Engine provides the core Docker technology that enables images and containers.

Simply said, if an image is a class, then a container is an instance of a class is a runtime object.

### Learning From:

1. javatpoint
2. Stackoverflow
3. YouTube & Google(Different blog and tutorial)
4. tutorialspoint