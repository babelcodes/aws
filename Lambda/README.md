# AWS Lambda

- [aws.amazon.com/lambda/](https://aws.amazon.com/fr/lambda/)

A Lambda function is a piece of code that is executed on AWS servers without having to configure a dedicated server to host it. This is great because:

- you only pay for it based on its running time, not for its idle time
- AWS can executes many copies of it if there is a surge in activity, so it is truly elastic, you don’t need to scale up/down your servers
- you don’t have to configure the server, you can write and test your code in the AWS console
This approach is called serverless for obvious reasons.

A Lambda function can be triggered by a user, by a CRON schedule, or by an Event.

## Use case

Update [Cloud Search](../CloudSearch) based on [S3](../S3) incoming files events.

- [Build your own Document Search Engine using Amazon Web Services](https://medium.com/devopslinks/build-your-own-document-search-engine-using-amazon-web-services-82d5b165d96c)
