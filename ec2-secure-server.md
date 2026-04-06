# Secure EC2 Server Deployment

## Objective
Deploy a secure server using Amazon EC2 and restrict SSH access.

## Services Used
- Amazon EC2
- Amazon VPC
- AWS IAM

## Steps Performed
1. Launched a t2.micro EC2 instance
2. Selected Amazon Linux OS
3. Created a key pair
4. Configured security group
5. Allowed SSH (port 22) only from my IP
6. Connected to the instance

## Security Configuration
- Restricted SSH access to my IP only
- Used key pair authentication instead of passwords

## Challenges Faced
- Failed SSH connection initially
- Resolved by correcting security group rules and troubleshooting connection issues

## What I Learned
- How to securely deploy a cloud server
- Importance of limiting SSH access

  ![image](https://github.com/user-attachments/assets/14138c79-4752-423b-a785-3e27b5bcf811)

