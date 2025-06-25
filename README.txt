XOps Static Web App (Dockerized)
================================
This is a simple HTML + CSS static website that says "Hello from XOps!", containerized using Docker and served via Nginx.
Project Contents
----------------
xops-static-app/
■■■ index.html # Single-page static website
■■■ Dockerfile # Docker instructions
■■■ README.md # This file

STEPS
------------
If running locally, the app will be accessible at:
http://localhost:8080

Cleaning Up
-----------
 docker ps # List running containers
 docker stop <container_id> # Stop your container
 docker images # View all Docker images