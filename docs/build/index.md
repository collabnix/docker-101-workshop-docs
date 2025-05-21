# Build: Containerizing Your Application

In this section, you'll learn how to containerize a full-stack application consisting of:

- A Spring Boot backend with RESTful APIs
- An Angular frontend
- A PostgreSQL database

## Objectives

By the end of this section, you will be able to:

1. Create a Dockerfile for a Spring Boot application
2. Create a Dockerfile for an Angular application
3. Create a `docker-compose.yml` file to run all services together
4. Configure proper networking between containers
5. Use environment variables for configuration

## Project Overview

The application is a simple CRUD app that manages students. Each student belongs to one of four houses: Gryffindor, Slytherin, Hufflepuff, or Ravenclaw.

### Backend (Spring Boot)

The backend is a Java 17 Spring Boot application that provides RESTful APIs for performing CRUD operations on the students database.

### Frontend (Angular)

The frontend is an Angular application that provides a user interface for interacting with the backend APIs.

### Database (PostgreSQL)

The application uses PostgreSQL as its database. The database schema includes a `students` table with fields for a student's name, house, and other attributes.

## Getting Started

Navigate to the `1-build` directory to begin:

```bash
cd 1-build
```

The directory contains the following:

- `backend-springboot/`: The Spring Boot application
- `frontend-angular/`: The Angular application
- `solution/`: Complete solution with Dockerfiles and docker-compose.yml

Follow the instructions in the next sections to containerize each part of the application.
