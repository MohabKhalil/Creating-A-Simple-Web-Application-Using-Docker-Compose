# Flask Redis Counter App

## Description

This is a simple Flask application that increments a counter every time the homepage is accessed. The counter is stored in a Redis database. The application is designed to run in a Docker environment, utilizing Docker Compose to manage the services and their configuration.

## Features

- Flask web application with a single endpoint that displays a hit count.
- Redis used for persisting and incrementing the hit count.
- Docker Compose for easy deployment and scaling.

## Project Structure

/project
├── app.py # Flask application file
├── requirements.txt # Python dependencies file
├── Dockerfile # Dockerfile for building the Flask application
└── docker-compose.yml# Docker Compose file to orchestrate the Flask app and Redis service
