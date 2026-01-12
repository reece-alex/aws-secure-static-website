# Architecture Diagram

This document describes the high-level architecture for the Secure Static Website on AWS.

## Traffic Flow
User → CloudFront (HTTPS) → S3 (Private Bucket)

## Components
- Amazon S3: Stores static website files in a private bucket
- Amazon CloudFront: Serves content securely and globally
- AWS Certificate Manager (ACM): Provides HTTPS encryption
- AWS WAF: Protects against common web attacks
- Amazon CloudWatch: Logs and monitors traffic and security events

## Security Design
- S3 bucket blocks all public access
- Only CloudFront can access the S3 origin
- HTTPS enforced using ACM
- WAF attached to CloudFront
- Logs enabled for monitoring and visibility

The architecture diagram image will be added to this folder.
