# helloworld


```
#  npm --version
6.14.5

# aws --version
aws-cli/2.0.38 Python/3.7.3 Linux/5.4.0-37-generic exe/x86_64.ubuntu.20

# serverless --version
Framework Core: 1.78.1
Plugin: 3.7.0
SDK: 2.3.1

# sls create --template aws-nodejs --path helloworld
Serverless: Generating boilerplate...
Serverless: Generating boilerplate in "/work/git/helloworld/helloworld"
 _______                             __
|   _   .-----.----.--.--.-----.----|  .-----.-----.-----.
|   |___|  -__|   _|  |  |  -__|   _|  |  -__|__ --|__ --|
|____   |_____|__|  \___/|_____|__| |__|_____|_____|_____|
|   |   |             The Serverless Application Framework
|       |                           serverless.com, v1.78.1
 -------'

Serverless: Successfully generated boilerplate for template: "aws-nodejs"


# sls deploy
Serverless: Packaging service...
Serverless: Excluding development dependencies...
Serverless: Creating Stack...
Serverless: Checking Stack create progress...
........
Serverless: Stack create finished...
Serverless: Uploading CloudFormation file to S3...
Serverless: Uploading artifacts...
Serverless: Uploading service helloworld.zip file to S3 (390 B)...
#Serverless: Validating template...
Serverless: Updating Stack...
Serverless: Checking Stack update progress...
...............
Serverless: Stack update finished...
Service Information
service: helloworld
stage: dev
region: us-east-1
stack: helloworld-dev
resources: 6
api keys:
  None
endpoints:
  None
functions:
  hello: helloworld-dev-hello
layers:
  None

******************************************************************************************************************
Serverless: Announcing Metrics, CI/CD, Secrets and more built into Serverless Framework. Run "serverless login" to activate for free..
******************************************************************************************************************

# sls invoke -f hello
{
    "statusCode": 200,
    "body": "{\n  \"message\": \"Go Serverless v1.0! Your function executed successfully!\",\n  \"input\": {}\n}"
}




```
