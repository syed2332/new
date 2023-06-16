# README

This README file provides instructions on how to clone and run the Dockerized Angular application.

## Prerequisites

Before getting started, ensure that you have the following prerequisites installed on your system:

- Git: [https://git-scm.com](https://git-scm.com)
- Docker: [https://www.docker.com](https://www.docker.com)

## Installation and Setup

Please follow the steps below to clone the source code, build the Docker image, and run the Angular application.

### Step 1: Clone Source Code

Clone the repository by running the following command in your terminal or command line:

```bash
git clone https://github.com/shihab-excelledia/docker-angular
```

### Step 2: Build the Docker Image

Navigate to the cloned project directory using the command line and execute the following command to build the Docker image:

```bash
docker build -t docker-angular .
```

### Step 3: Run the Angular App in the Container

Run the following command to start the Angular application inside a Docker container:

```bash
docker run -d -p "4202:4200" docker-angular
```

### Step 4: Access the Application

Once the Docker container is running, you can access the Angular application by opening your web browser and visiting [http://localhost:4201](http://localhost:4201).

## Conclusion

By following these steps, you should now have the Dockerized Angular application up and running on your local machine. Feel free to explore and interact with the application using the provided URL. If you encounter any issues or have any questions, please refer to the project's documentation or contact the repository owner.
