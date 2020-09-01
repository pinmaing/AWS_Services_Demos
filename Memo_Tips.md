# Tips for AWS related Service

## Lambda

### How do I hide Lambda environment variables from IAM users?
https://aws.amazon.com/jp/premiumsupport/knowledge-center/lambda-environment-variables-iam-access/


### Tutorial: Configuring a Lambda function to access Amazon RDS in an Amazon VPC
https://docs.aws.amazon.com/lambda/latest/dg/services-rds-tutorial.html

_similar referene_
https://recipe.kc-cloud.jp/archives/9149

### AWS Lambda Tutorial - Connect to MySQL
https://www.youtube.com/watch?v=cGYknt3xIvM

### How to Query RDS MySQL From AWS Lambda in Python | Step by Step Tutorial
https://www.youtube.com/watch?v=vyLvmPkQZkI

### Good Reference to understand S3,RDS(MySQL),Lambda combination
https://github.com/diegonalvarez/bi-step-functions

## Good Reference to understand S3, EC2, Lambda combination with SFTP
https://exploitnetworking.com/en/aws-en/import-paramiko-to-aws-lambda

### Good Reference to understand S3, EC2, Lambda combination with SSH
https://www.transposit.com/blog/2019.12.18-using-lambda-as-an-ssh-proxy/
https://oji-cloud.net/2019/11/28/post-3665/

### Lambda Layer
https://qiita.com/t_okkan/items/394a15577bd1aad46ec3#lambda%E9%96%A2%E6%95%B0%E3%81%ABlayer%E3%82%92%E8%BF%BD%E5%8A%A0%E3%81%99%E3%82%8B
_it is important to put desire package under "python" folder before zip_

## KMS
### Creating keys
https://docs.aws.amazon.com/kms/latest/developerguide/create-keys.html

## Step Function

### Launch StepFunctions with CloudWatch Events
https://dev.classmethod.jp/articles/cloudwatch-events-to-stepfunctions/

### Call Amazon SNS with Step Funct
https://docs.aws.amazon.com/step-functions/latest/dg/connect-sns.html

### Input Output filtering
https://docs.aws.amazon.com/step-functions/latest/dg/concepts-input-output-filtering.html

### Amazon States Language (specific sample)
https://aws.amazon.com/blogs/aws/aws-step-functions-adds-updates-to-choice-state-global-access-to-context-object-dynamic-timeouts-result-selection-and-intrinsic-functions-to-amazon-states-languages/

## VPC

### What is VPC peering?
https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html

### VPC peering basics
https://docs.aws.amazon.com/vpc/latest/peering/vpc-peering-basics.html

### Creating and accepting a VPC peering connection
https://docs.aws.amazon.com/vpc/latest/peering/create-vpc-peering-connection.html#create-vpc-peering-connection-remote

### Updating your Route tables for a VPC peering connection
https://docs.aws.amazon.com/vpc/latest/peering/vpc-peering-routing.html

### Configurations with routes to an entire CIDR block
https://docs.aws.amazon.com/vpc/latest/peering/peering-configurations-full-access.html#two-vpcs-full-access


### Troubleshoot for VPC Peering
_allow DNS resolution_ as point for me..

https://stackoverflow.com/a/46331624/10325383

### VPC Endpoint for Amazon S3
https://aws.amazon.com/jp/blogs/aws/new-vpc-endpoint-for-amazon-s3/

### Restricting Access to a Specific VPC Endpoint
https://docs.aws.amazon.com/AmazonS3/latest/dev/example-bucket-policies-vpc-endpoint.html#example-bucket-policies-restrict-accesss-vpc-endpoint