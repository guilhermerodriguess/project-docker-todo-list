# Project One For All

The One For All Project is a full-stack task management application built to run entirely on Docker. It uses the advanced concepts of containers and orchestration to connect and manage the front-end and back-end components of the application, as well as a test application that validates the communication between the parts.

## Installation

To run the project, you need to have Docker installed in your environment. Orchestration is done through Docker Compose.

Follow the steps below to configure and run the project:

1. Clone the repository to your local environment.
2. Navigate to the project's root directory.
3. Run `docker-compose up -d` to start the application.

## Project description

The One For All Project is based on a tasks application that is containerized using Docker. It includes settings for the frontend, backend, and also a test application that validates the communication between them. Docker Compose is used to orchestrate the operation of these different parts of the application.

The project includes a series of Docker commands that are used to configure and manage the application, including creating containers, running commands inside containers, removing containers, and much more. Each Docker command is kept in its own file for easy maintainability.

Front-end and back-end applications are built from Dockerfile files. The frontend is created from the "todofrontend" image, and the backend from the "todobackend" image. The "todotests" image is used to create the test application.

## Functionalities

- Application of containerized full-stack tasks using Docker.
- Custom Dockerfile files to create Docker images for the frontend, backend and test application.
- Docker Compose to orchestrate the operation of the different parts of the application.
- Custom Docker commands to manage the application.
- Test application to validate the communication between frontend and backend.

## Contributing

We would be happy to receive contributions to the project. If you find a bug, have a suggestion for improvement or want to add new functionality, please create an issue or a pull request.

## License

This project is licensed under the MIT license.
