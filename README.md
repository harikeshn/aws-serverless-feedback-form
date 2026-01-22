AWS 3-Tier Serverless Feedback Form

OVERVIEW
This project is a serverless feedback form built using AWS services.
Users submit feedback through a web page, and the data is stored securely in AWS.

AWS SERVICES USED
- Amazon S3
- Amazon CloudFront
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- AWS IAM
- Amazon SNS (optional)

PROJECT FLOW
User submits feedback →
API Gateway →
Lambda →
DynamoDB
(Optional SNS notification)

WHAT THIS PROJECT SHOWS
- Serverless architecture
- No servers to manage
- Secure and scalable design
- Real-time data storage

RESULT
Feedback submitted from the UI is successfully stored in DynamoDB.
