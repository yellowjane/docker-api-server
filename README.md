# Dockerized FastAPI Server
This project demonstrates a simple REST API service built with FastAPI and containerized using Docker.

## Features
- Rest API using FastAPI
- Task management endpoints
- Docker container deployment 

## Endpoints
GET /tasks
POST /tasks

## Run locally
pip install -r requirements.txt
uvicorn main:app --reload