# Hosting a Static Website on AWS with Lambda

This project outlines hosting a static website on AWS, utilizing S3 for storage, CloudFront for content delivery, Route 53 for DNS management, DynamoDB for database services, and AWS Lambda for serverless computing.

## Architecture

The architecture includes:
- **Amazon S3**: Hosts static website files.
- **Amazon CloudFront**: Distributes content globally.
- **Amazon Route 53**: Manages the domain name.
- **Amazon DynamoDB**: Stores dynamic content data.
- **AWS Lambda**: Executes backend logic without provisioning or managing servers.

## Components

### Amazon S3
Stores and serves the website's static files (HTML, CSS, JS).

### Amazon CloudFront
Caches content at edge locations for faster delivery.

### Amazon Route 53
Manages the DNS settings for custom domain, directing traffic to the CloudFront distribution.

### Amazon DynamoDB
Provides a NoSQL database to store and retrieve dynamic content efficiently.

### AWS Lambda
Executes code in response to triggers (e.g., API requests) without managing servers.

## Best Practices

- Using CloudFront for global content delivery and caching.
- Monitoring website traffic and access patterns using AWS CloudWatch.
- using AWS IAM roles and policies for fine-grained access control to AWS services.


