# Skill Up - FastAPI - Departments - o.khudakov

## Name
skill-up-fastapi-departments

## Description
Basic learning course

## Installation
You must have docker and docker compose installed on your machine
you must have .env file with all needed variables which are
APP_HOST="0.0.0.0"
APP_PORT="8000:8000"
DB_HOST="db"
DB_PORT="5432:5432"
DB_NAME="postgres"
DB_USERNAME="postgres"
DB_PASSWORD="postgres"
then navigate to the root folder of the project(/skill-up-fast-api-department-o.khudakov/)
type in 'docker compose up' command
now you can access the app
GET request to root("/") will redirect you to the documentation page
it has default employees and departments which you can find in very first migration version
