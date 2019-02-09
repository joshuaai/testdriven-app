# Test Driven App with Flask, React, and Docker

The app is a code evaluation tool built on the microservices concept.

## Key Commands

- Building and updating a container - `docker-compose -f docker-compose-dev.yml up -d --build`

- Fire up the container - `docker-compose -f docker-compose-dev.yml up -d`

- To view the logs - `docker-compose -f docker-compose-dev.yml logs`

- To run the tests - `docker-compose -f docker-compose-dev.yml exec users python manage.py test`

- To work with the python shell - `docker-compose -f docker-compose-dev.yml exec users flask shell`

- To use the postgres shell - `docker-compose -f docker-compose-dev.yml exec users-db psql -U postgres`