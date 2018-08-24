# AWS Step Functions Scheduled Invocation Demo

This is a Java version of [Schedule a Serverless Workflow ](https://aws.amazon.com/getting-started/tutorials/scheduling-a-serverless-workflow-step-functions-cloudwatch-events/)


## Prerequisites
* [SAM CLI](https://github.com/awslabs/serverless-application-model) installed.

## How to run
First create an S3 bucket with some name. Then edit `package-and-deploy.sh.tmp` and replace <BUCKET_NAME> with that name.
Then rename  `package-and-deploy.sh.tmp` to `package-and-deploy.sh` and run `sh package-and-deploy.sh`

