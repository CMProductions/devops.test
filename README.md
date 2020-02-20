# Devops Kubernetes test

## Description

Build a simple REST API. This API code needs to run in a a kubernetes cluster.

You may use any k8s implmementation you like. You can use as many pods , and containers , as you need.

## API Specification

GET /user/{id} - Retrieves a specific user

POST /user - Creates a new user

DELETE /user/{id} - Deletes a specific user

## Restrictions

You can use any language you want for the API , although extra points if you use python or go.

You can use any database backend you want , or none (You can use In Memory DB without persistence).  

Use Makefile as the single entrypoint , to control the app flow.

## TO BE DONE:
### Implement the following commands:

- make build: : Build and push the required image/s.

- make deploy : Deploy the app to the cluster.

- make test : Run tests to check that the API working (Cover all the methods)

We expect you provide a zip, with what you did.

## What we will evaluate

 - Reliability
 - Code structure
 - Tool/Libraries usage
 - How would you implement deployment pipeline
 - Tests
 - Logging (what would you log , where you would store it etc)
 - Documentation
 - Further instructions to move it to production
