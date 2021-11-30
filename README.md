# Web Service
This project contains code which builds the web service for our cluster

## Example .env
```
STAGE=dev
REGION=us-east-1
```

## Deployment
This is a Serverless Framework application and can be deployed using standard
serverless cli commands. The application is deployed using the STAGE and REGION parameters defined in the .env file.
```
sls deploy
```
