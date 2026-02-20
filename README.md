# AWS S3 Least-Privilege Security Project

## Overview
This project demonstrates how to securely manage an AWS S3 bucket using least-privilege IAM policies. CloudTrail is enabled to log S3 data events for auditing and monitoring purposes. The goal is to provide controlled access while maintaining visibility for compliance and security.

## Key Features
- **Least-Privilege IAM Policy**: Users can only list, upload, and download objects in the designated S3 bucket.  
- **CloudTrail Logging**: Tracks all S3 data events for audit and compliance purposes.  
- **Proof of Work**: Includes screenshots and the policy JSON to demonstrate implementation.

## Files
- `1-s3-upload-proof.png` → Screenshot of uploaded file in S3  
- `2-iam-policy-proof.png` → Screenshot of IAM policy in AWS console  
- `S3SecureProjectPolicy.json` → Actual IAM policy JSON  

## Skills Demonstrated
- AWS S3 configuration  
- IAM least-privilege access control  
- CloudTrail audit logging  
- Cloud security best practices

## How to Use
1. Clone this repository.  
2. Review the IAM policy JSON file to understand permission boundaries.  
3. Review the screenshots for visual confirmation of S3 and IAM setup.  
4. Apply similar configurations in your own AWS account for learning or portfolio demonstration.
