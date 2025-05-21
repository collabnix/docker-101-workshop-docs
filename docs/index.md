# Docker 101 Workshop

Welcome to the Docker 101 Workshop! This workshop will guide you through the process of containerizing a CRUD web application that allows users to add, update, and delete "students" in a PostgreSQL database. Students have a name and belong to one of four houses: Gryffindor, Slytherin, Hufflepuff, or Ravenclaw.

## Tech Stack

- **Backend**: Java 17, Spring Boot, Maven, PostgreSQL
- **Frontend**: Angular, Bootstrap
- **Containerization**: Docker, Docker Compose

## Project Structure

- `backend-springboot/`: Java Spring Boot backend API
- `frontend-angular/`: Angular frontend application

## API Endpoints

- `GET /api/students`: Get all students
- `GET /api/students/{id}`: Get a student by ID
- `POST /api/students`: Create a new student
- `PUT /api/students/{id}`: Update a student
- `DELETE /api/students/{id}`: Delete a student

## Workshop Overview

This workshop is divided into four main sections:

1. **Build**: Learn how to containerize Spring Boot, Angular, and PostgreSQL applications
2. **Test**: Run, troubleshoot, and test containerized applications
3. **Deploy**: Deploy containers to Kubernetes
4. **CDE**: Set up a Container Development Environment

## Prerequisites

- Git
- Docker Desktop
- Basic knowledge of:
  - Java/Maven
  - Node.js/Angular
  - Docker concepts

## Getting Started

Clone the repository and follow along with the instructions in each section:

```bash
git clone https://github.com/collabnix/docker-101-workshop.git
cd docker-101-workshop
```

Each section contains detailed instructions, exercises, and solutions to help you learn Docker and containerization principles with practical examples.
