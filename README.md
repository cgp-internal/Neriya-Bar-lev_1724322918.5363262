Monorepo containing three distinct projects: frontend, backend, and workers.

## Frontend Project

The frontend project uses React and Mantine library for UI components. It is built using Vite and configured with TypeScript.

### Exposes

* `frontend/package.json`: Frontend package dependencies
* `frontend/vite.config.js`: Vite configuration for frontend development
* `frontend/src/main.tsx`: Main entry point for the React application in TypeScript
* `frontend/components`: React components using Mantine library
* `frontend/hooks`: Custom React hooks
* `frontend/utils`: Utility functions for the frontend application
* `frontend/tsconfig.json`: TypeScript configuration for the frontend application

## Backend Project

The backend project uses FastAPI for building RESTful APIs and is written in Python.

### Exposes

* `backend/requirements.txt`: Python dependencies for the backend application
* `backend/main.py`: Main entry point for the FastAPI application
* `backend/app/models`: Data models for the FastAPI application
* `backend/app/routers`: RESTful API routers using FastAPI
* `backend/app/utils`: Utility functions for the backend application
* `backend/tests`: Unit tests for the backend application

## Workers Project

The workers project contains multiple workers, each with its own set of tasks. They share a common set of dependencies and environment configuration.

### Exposes

* `workers/requirements.txt`: Shared Python dependencies for the workers
* `workers/worker1/main.py`: Main entry point for worker 1
* `workers/worker1/tasks`: Tasks performed by worker 1
* `workers/worker2/main.py`: Main entry point for worker 2
* `workers/worker2/tasks`: Tasks performed by worker 2
* `workers/env`: Shared environment configuration for the workers