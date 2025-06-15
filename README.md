# FitTrack - Gym Workout Tracking Application

A full-stack application for tracking gym workouts, creating personalized routines, and managing training programs.

## Features

- Create and manage workout programs
- Design weekly workout schedules
- Track exercises with rep ranges and RPE (Rate of Perceived Exertion)
- Add notes and progress tracking
- User authentication and profile management

## Tech Stack

### Backend

- Java 17
- Spring Boot 3.x
- Spring Security
- Spring Data JPA
- PostgreSQL
- Maven

### Frontend

- React 18
- TypeScript
- Material-UI
- React Router
- Axios

## Project Structure

```
fittrack/
├── backend/           # Spring Boot application
└── frontend/         # React application
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory
2. Run `mvn spring-boot:run`
3. The server will start on `http://localhost:8080`

### Frontend Setup

1. Navigate to the frontend directory
2. Run `npm install`
3. Run `npm start`
4. The application will start on `http://localhost:3000`

## API Documentation

API documentation will be available at `http://localhost:8080/swagger-ui.html` when the backend is running.
