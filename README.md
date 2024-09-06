Project Name

This project is a full-stack application featuring a backend API server and a frontend React application with chart visualizations. The setup is containerized using Docker and Docker Compose, allowing for easy setup and deployment.
Table of Contents

    Setup Instructions
    Libraries and Tools Used
    Approach and Thought Process

Setup Instructions
Prerequisites

    Docker installed on your machine.
    Docker Compose installed.

Steps to Set Up and Run the Application

    Clone the Repository

    bash

git clone https://github.com/yourusername/yourproject.git
cd yourproject

Build and Start the Application

Use Docker Compose to build and start both backend and frontend services:

bash

docker-compose up --build

Access the Application

    Frontend: Open your browser and go to http://localhost:3000.
    Backend API: The backend API is available at http://localhost:8000.

Stopping the Application

To stop the application and remove the containers, run:

bash

    docker-compose down

Libraries and Tools Used
Backend

    Python 3.10: The core language used for the backend server.
    FastAPI: A modern, fast web framework for building APIs.
    Uvicorn: A lightning-fast ASGI server implementation for running FastAPI.
    Pandas: Used for data manipulation and analysis.

Frontend

    React: The core library used for building the user interface.
    React Query (@tanstack/react-query): Manages server-state, fetching, caching, and updating data in the app.
    Chart.js: A JavaScript library that allows for drawing charts in the frontend.
    react-chartjs-2: A React wrapper for Chart.js to create charts easily.
    chartjs-chart-financial: Adds support for financial charts, including candlestick charts.

Docker

    Docker: Used to containerize the application for consistent environments across development and production.
    Docker Compose: Simplifies multi-container Docker applications.