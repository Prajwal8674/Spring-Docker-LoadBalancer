# Spring Boot Load Balancer using Docker & Nginx

## Overview
This project demonstrates a simple load balancing architecture using Spring Boot applications running inside Docker containers and an Nginx reverse proxy.

## Architecture

Client -> Nginx Load Balancer -> Multiple Spring Boot Instances

## Tech Stack
- Java
- Spring Boot
- Docker
- Nginx

## Features
- Multiple Spring Boot containers
- Nginx reverse proxy load balancing
- Round Robin request distribution
- Containerized microservice architecture

## How to Run

1. Build the project
mvn clean package

2. Start containers
docker-compose up --build

3. Open browser
http://localhost:8080

Refresh the page multiple times to see requests routed to different containers.

## Concepts Demonstrated
- Load balancing
- Horizontal scaling
- Containerization
- Reverse proxy architecture
