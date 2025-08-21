# Task Management Application

This is a Task Management Application I built to strengthen my skills in full-stack development. It uses React (frontend), NestJS (backend), and PostgreSQL (database). The app allows users to create, update, and track tasks through a responsive UI and secure REST APIs.

## Features

- Create, read, update, and delete tasks
- Mark tasks as pending or completed
- Responsive design
- Real-time updates
- RESTful API

## Tech Stack

### Frontend

- React
- TypeScript
- Redux Toolkit
- Vite
- Custom CSS

### Backend

- NestJS
- TypeScript
- PostgreSQL
- TypeORM
- Class Validator
- Class Transformer

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL (v14 or higher)
- Docker and Docker Compose (optional, for containerized deployment)

## Running the Application
The app can be run locally or with Docker.  
For simplicity, I’ve included setup instructions in the backend/frontend README files.  
- Frontend: `cd frontend && npm install && npm run dev`  
- Backend: `cd backend && npm install && npm run start:dev`


## Deployment / Setup
This project is containerized using Docker and can also be run locally with Node.js and PostgreSQL.  
For detailed setup steps, please check the backend and frontend directories.


## API Endpoints

- `GET /tasks` - Get all tasks
- `POST /tasks` - Create a new task
- `GET /tasks/:id` - Get a specific task
- `PATCH /tasks/:id` - Update a task
- `DELETE /tasks/:id` - Delete a task
- `GET /health` - Check the health of the application

# My Contribution

Implemented CRUD operations and REST APIs using NestJS +    PostgreSQL

Integrated Redux Toolkit for state management in React

Configured Docker for full-stack containerized deployment

Documented API endpoints and structured code for clarity


# Future Improvements

Add task priority and due dates

Implement role-based access (Admin/User)

Integrate GraphQL and WebSockets for real-time updates

Add unit & integration tests with Jest