# What is it? 
- Secure cloud services platform, 
- offering compute power, 
- database storage, 
- content delivery and other functionality to help businesses scale and grow

## Where to Start? 
https://aws.amazon.com/getting-started/

1. Launch a Linux VM using EC2 
2. Launch a Word Press Website with EC2 and AWS 
3. Launch a Web Application using AWS Elastic Beanstalk
4. Update a Web Application using AWS Elastic Beanstalk
5. Store and Retrieve a File using S3 buckets
6. Store Multiple Files using S3 and AWS CLI 
7. Create and Query a NoSQL Table using Amazon Dynamo DB 
8. Register a Domain Name using Amazon Route 53 

# Overview on AWS  

## Zone 
- An availability zone is a separate "failure zone" within a given region that can have resources instantiated in. Each region has it's own power grid, and physical set of hardware and resources. Availability zones within a given region have a shared management interface/infrastructure.

## Region 
-  us-east-1 (Virginia), us-west-1 (N. California), us-west-2 (Oregon), eu-west-1 (Ireland), ap-southeast-1 (Singapore), ap-northeast-1 (Tokyo), ap-southeast-2 (Sydney), sa-east-1 (Sao Paulo)

## EC2
- Service cloud platform by AWS 
- Allows users to instantiate various types of VM's


## EBS
- Block storage persistenc 
- EC2 volumes 
- Replicated in Availability Zone 

## S3
- Storage for internet 
- any data in any format
- multi object delete 
- REST based

## CLI
- Linux Shells
- Windows cmd
- Remotely 

## Dynamo
-  NoSQL db
-  DynamoDB stores three geographically distributed replicas
- runs exclusively on Solid State Drives
- Atomic updates via  increment or decrement a numeric attribute in a row using a single API call

## Route 53
- DNS 
- Health checks, endpoints, monitoring or alarm 
- REST API Standards

# Lambda
- Java, Node, Python, C# 
-  code must be written in a “stateless” style
- Local file system access, child processes, 
- similar artifacts may not extend beyond the lifetime of the request, 
- and any persistent state should be stored in Amazon S3, Amazon DynamoDB, 
- or another Internet-available storage service. Lambda functions can include libraries, even native one

## for DevOps 
- Automation
- Fully Managed Services
- Secure 
- Built for Scaling
- PAYG
- Programmable  
- Large Partner EcoSystem 

