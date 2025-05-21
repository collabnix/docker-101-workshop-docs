# Docker Workshop

# **Build, Run, Deploy: a Full-Stack App with Spring Boot, AngularJS, and PostgreSQL**

## **Workshop Description:**

In this hands-on, in-person workshop, developers will gain practical experience building, running, testing, and deploying a full-stack containerized application. Participants will work with a real-world example that combines a **Spring Boot API backend**, an **AngularJS frontend**, and a **PostgreSQL database**, all orchestrated using Docker.

By the end of the session, developers will walk away with a clear understanding of how to:
?	Containerize backend, frontend, and database services
?	Run everything together using Docker Compose
?	Troubleshoot the application locally and prepare it for cloud deployment

This workshop is ideal for developers with some experience in Java or frontend development who are looking to sharpen their DevOps and containerization skills.

## **Technology Stack:**
**Required**
* Git
* Docker Desktop

**Languages**
* Java 17 / Maven
    * Spring Boot 3.2
* Node.js 20
    * Angular 18
* PostgreSQL 14
---

**Workshop Agenda:**

**? Duration: 4.5 hours with breaks**

---

**? 9:30 AM ? 10:00 AM**

**Welcome & Setup**

- Introductions
- Workshop goals
- Checking prerequisites (Docker, Docker Compose, Git, Java, Node.js)
- Clone starter project and verify environment

---

**? 10:00 AM - 10:45 AM**

**Part 1: Backend Containerization (Spring Boot + PostgreSQL)**

?	Overview of Spring Boot and PostgreSQL integration

?	Dockerfile for Spring Boot

?	Writing a docker-compose.yml to include Postgres

?	Connecting backend to database using environment variables

? **Hands-on Exercise:** Run Spring Boot with a containerized Postgres instance

---

? **Break (15 mins)**

---

**? 11:00 AM ? 12:00 PM**

**Part 2: Frontend Containerization (AngularJS)**

?	Overview of AngularJS application structure

?	Creating a Dockerfile for a static site using NGINX

?	Proxying API requests to backend

? **Hands-on Exercise:** Build and run frontend and backend together using Docker Compose

---

? **Lunch (1 hour)**

---

**? 1:00 PM ? 1:45 PM**

**Part 3: Running and Troubleshooting**

?	Run all services together

?	Troubleshooting container networking, logs, and errors

?	Health checks and startup dependencies

?	Database seeding/migrations for test environments

?	Using Docker volumes for persistent data (optional)

? **Hands-on Exercise:** Run backend and frontend together using `docker compose`

---

? **Break (15 mins)**

---

**? 2:00 PM ? 2:45 PM**

**Part 4: Deployment**

- Kubernetes / KinD overview
- Manifests
- Docker compose bridge

? **Hands-on Exercise:** Deploy the application to KinD

---

**? 2:45 PM ? 3:00 PM**

**Wrap-Up & Q&A**

- Recap
- New Docker features (optional)
- Q&A

---
