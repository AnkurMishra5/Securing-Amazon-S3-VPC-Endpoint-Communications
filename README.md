# Securing-Amazon-S3-VPC-Endpoint-Communications
This project demonstrates how to securely access Amazon S3 from an EC2 instance located in a private subnet using Amazon VPC endpoints. This project demonstrates how to securely access Amazon S3 from an EC2 instance located in a private subnet using Amazon VPC endpoints. By configuring a VPC endpoint, we enable private subnet resources to communicate with Amazon S3 without exposing them to the public internet. Additionally, a VPC endpoint policy is applied to restrict access to specific S3 resources, ensuring data security and controlled access within the AWS environment.

**Technology Stack**
Amazon VPC: For creating isolated public and private subnets.
Amazon EC2: For computing.
Amazon S3: For storing and retrieving demo files.
VPC Endpoint: For establishing private connectivity to Amazon S3.
VPC Endpoint Policy: To limit access to specific S3 resources.
AWS CLI: For configuration and verification.
