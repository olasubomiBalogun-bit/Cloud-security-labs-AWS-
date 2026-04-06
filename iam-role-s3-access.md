# IAM Role for EC2 to Access S3

## Objective
Allow an EC2 instance to access S3 securely without using access keys.

## Services Used
- AWS IAM
- Amazon EC2
- Amazon S3

## Steps Performed
1. Created a new IAM role for EC2
2. Attached AmazonS3ReadOnlyAccess policy
3. Assigned the role to EC2 instance

## Security Concept
- Used IAM roles instead of hardcoding credentials
- Applied least privilege principle

## What I Learned
- How IAM roles provide secure access
- Why access keys should not be stored on servers


  ![image](https://github.com/user-attachments/assets/24474006-03bd-4fba-bb09-4c115f1cbbea)


  ## Real-World Relevance

This lab demonstrates how to prevent common cloud security issues such as:
- Unauthorized server access
- Credential exposure
- Public data leaks

