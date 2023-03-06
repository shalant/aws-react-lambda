# Serverless React Invoice App
from Code Engine's youtube channel: https://www.youtube.com/watch?v=Bro0uFVDrWY&t=462s

## Description
Built a simple React app that aspires to implement CRUD functionality. This application only gets data.

## AWS features
The react app is served from an S3 bucket. The code gets data from an API Gateway endpoint. Data is stored in Dynamo DB. A Lambda function is called to make a GET request to serve data to the API. The front-end application simply displays the data in a table.

## Deployment
http://invoice-processing-aws-dr.s3-website-us-east-1.amazonaws.com/

## Future development
I would love to set up a pipeline using additional AWS services

