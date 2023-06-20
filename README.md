# Docker Compose Setup with Reverse Proxy

This repository contains a Docker Compose setup for running WordPress, MySQL, and phpMyAdmin with a reverse proxy using NGINX.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following software installed on your machine:

- Docker: [Installation Guide](https://docs.docker.com/engine/install/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

### Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/jiienc/DockerPress.git

2. Navigate to the cloned repository:

   ```shell
   cd DockerPress

3. Open the .env file and modify the values according to your requirements.
   
   ```shell
   nano .env
   
4. Start the Docker Compose services:
   
   ```shell
   docker-compose up -d

5. Access WordPress in your web browser:

   Open [http://localhost:8080](http://localhost:8080) in your web browser to access WordPress.

6. Access phpMyAdmin in your web browser:
   
   Open [http://localhost:8080/pma](http://localhost:8080/pma) in your web browser to access phpMyAdmin.

## Configuration

The main configuration files for this setup are:

- docker-compose.yml: Defines the services, ports, environment variables, and dependencies.
- nginx.conf: Contains the NGINX configuration for the reverse proxy.

## Acknowledgments

- NGINX
- WordPress
- MySQL
- phpMyAdmin
