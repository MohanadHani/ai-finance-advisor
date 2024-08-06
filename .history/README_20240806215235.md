# FinAI Advisor

## Project Overview

An AI-Powered Personal Finance Advisor.

## Directory Structure

- backend: Contains microservices for user, transaction, investment, advice, and notification services.
- frontend: Contains the React application.
- deployment: Contains Docker and Kubernetes deployment configurations.

## Installation

### Backend

1. Navigate to the backend directory: `cd backend`
2. Create a virtual environment: `python3 -m venv env`
3. Activate the virtual environment: `source env/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`

### Frontend

1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`

## Running the Project

### Backend

1. Navigate to the backend directory: `cd backend`
2. Start the FastAPI server: `uvicorn user_service.main:app --reload`

### Frontend

1. Navigate to the frontend directory: `cd frontend`
2. Start the React development server: `npm start`
