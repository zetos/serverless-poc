# Serverless POC

A poc to test the [Serverless Framework](https://serverless.com).

## Setup:

Requires: `npm i serverless --global`  
Config: `serverless config credentials -o --provider aws --key=<YOUR-KEY> --secret <YOUR-SECRET>`  
Deploy: `serverless deploy -v`  
Test a Lambda Function: `serverless invoke -f hello -l`  
Delete serveless related services from AWS: `serverless remove`

