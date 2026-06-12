# Infrastructure as Code using AWS CDK

## Project Overview

This project demonstrates Infrastructure as Code (IaC) using AWS CDK and AWS CloudFormation.

The infrastructure is defined in TypeScript and deployed automatically to AWS.

## Architecture

AWS CDK
↓
CloudFormation
↓
Amazon S3 Bucket

## Technologies Used

- AWS CDK
- AWS CloudFormation
- Amazon S3
- AWS CLI
- TypeScript
- IAM

## Features

- Infrastructure as Code
- Automated deployment
- CloudFormation stack creation
- S3 bucket provisioning
- Versioned storage

## Deployment Commands

```bash
cdk synth
cdk deploy
```

## Resources Created

- Amazon S3 Bucket
- CDK Metadata

## Screenshots

See the screenshots folder.

## Learning Outcomes

- Infrastructure as Code
- AWS CDK
- CloudFormation
- Resource Automation
- Cloud Resource Management

# Screenshots
![01-project-structure](<Screenshot 2026-06-12 124537.png>)

![02-cdk-code](<Screenshot 2026-06-12 124552.png>)

![03-aws-authentication](<Screenshot 2026-06-12 124904.png>)

![04-cdk-synth](<Screenshot 2026-06-12 124634.png>)

![05-cdk-deploy-success](<Screenshot 2026-06-12 124648.png>)

![06-cloudformation-stack](<Screenshot 2026-06-12 123131.png>)

![07-cloudformation-resources](<Screenshot 2026-06-12 125113-1.png>)

![08-s3-bucket](<Screenshot 2026-06-12 125203.png>)

![09-bucket-upload-test](<Screenshot 2026-06-12 124824.png>)

## Project Summary

This project demonstrates Infrastructure as Code (IaC) using AWS CDK and AWS CloudFormation. The infrastructure was defined in TypeScript and deployed automatically to AWS using the AWS CLI. Through this project, an Amazon S3 bucket was provisioned and managed without manual resource creation in the AWS Console. The project showcases cloud automation, resource provisioning, infrastructure management, and modern DevOps practices while utilizing AWS Free Tier services. This implementation helped in understanding AWS CDK, CloudFormation stacks, IAM authentication, deployment workflows, and the benefits of managing cloud infrastructure through code.