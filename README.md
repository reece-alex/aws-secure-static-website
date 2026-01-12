# Secure Static Website on AWS

## Project Overview
This project demonstrates how to design and deploy a secure, production-style static website on AWS using core cloud services. The focus is on security, scalability, and best practices.

The project is built to reflect the responsibilities of a Junior Cloud / Cloud Support Engineer.

## Problem Statement
Small businesses often need a fast, secure, and low-cost website but lack the expertise to configure AWS securely. Common risks include:
- Publicly exposed S3 buckets
- No HTTPS encryption
- No protection against malicious traffic
- No logging or monitoring

## Solution Overview
This project deploys a secure static website using:
- Amazon S3 (private bucket)
- Amazon CloudFront (CDN)
- AWS Certificate Manager (HTTPS)
- AWS WAF (security rules)
- Amazon CloudWatch (logging and monitoring)

## High-Level Architecture
User → CloudFront (HTTPS) → S3 (Private Bucket)

##Security:
- AWS WAF attached to CloudFront
- CloudWatch logging enabled

## Project Status
- [x] Repository setup
- [x] Architecture diagram
- [ ] S3 configuration
- [ ] CloudFront distribution
- [ ] ACM certificate
- [ ] WAF rules
- [ ] Logging & monitoring

## Learning Outcomes
- Secure AWS architecture
- CDN and HTTPS configuration
- Web security fundamentals
- Cloud monitoring basics
