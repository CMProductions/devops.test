# devops.test

## Description
Build a simple REST API. This API code needs to run in a Docker container.

## API Specification
GET /user/{id} - Retrieves a specific user

POST /user - Creates a new user

DELETE /user/{id} - Deletes a specific user

## Restrictions
You can use any language you want for the API

You can use any database system you want or none (You can use In Memory DB without persistence)

Use Makefile as the single entrypoint to run and stop the docker environment

## TO BE DONE:
### Implement the following commands:

- make dev : Start the dev environment
- make test : Run tests to check that the API working (Cover all the methods)
- make clean : Stop and remove all the containers and images

### Further instructions

Provide some instructions or guide to move this to a production environment

## What we will evaluate
 - Reliability
 - Code structure
 - Tool/Libraries usage
 - Tests
 - Documentation
 - Further instructions to move it to production
