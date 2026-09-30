# 🔐 AWS S3 Security & Data Protection Lab

## 📌 Project Overview:
This project demonstrates the implementation of security best practices for protecting data stored in Amazon S3.

The lab focuses on securing an S3 bucket using AWS security controls such as Block Public Access, server-side encryption, bucket versioning, IAM least-privilege access, bucket policies, and AWS CloudTrail monitoring.

The project also includes security testing to verify that authorized operations are allowed while unauthorized actions are denied.

## 🎯 Project Objectives:
- Create and securely configure an Amazon S3 bucket.
- Prevent unauthorized public access to stored data.
- Protect data at rest using S3 server-side encryption.
- Enable S3 Versioning for data recovery and protection.
- Implement least-privilege access using AWS IAM.
- Configure bucket-level security policies.
- Test allowed and denied S3 operations.
- Monitor S3-related activity using AWS CloudTrail.
- Document security controls and testing results.

## 🔒 Security Implementation

### 1. Secure S3 Bucket Creation
Created a dedicated Amazon S3 bucket for this cloud security lab.

The initial configuration includes:
- S3 Object Ownership with ACLs disabled.
- Block Public Access enabled.
- Server-side encryption using Amazon S3 managed keys (SSE-S3).
- Resource tags for project identification.
- Object Lock disabled for the initial lab configuration.

This bucket will be used to implement and test additional data protection and access-control mechanisms.
#### Evidence

![S3 Bucket Created](screenshots/Screenshot of (1) S3 Bucket creation.png)
