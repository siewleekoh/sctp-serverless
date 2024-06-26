# sctp-serverless
# Serverless Framework Node HTTP API on AWS

This template demonstrates how to make a simple HTTP API with Node.js running on AWS Lambda and API Gateway using the Serverless Framework.

This template does not include any kind of persistence (database). For more advanced examples, check out the [serverless/examples repository](https://github.com/serverless/examples/) which includes Typescript, Mongo, DynamoDB and other examples.

- deploy to AWS
```
serverless deploy
```

- install plugin
```
sudo npm install serverless-offline --save-dev
```

- test offline
```
serverless offline or sls offline.
```

- remove resources
```
serverless remove
```



## Alternative way to start serverless project on AWS

```
serverless 
```