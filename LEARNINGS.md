# Learnings and Design Decisions

## Architectural Reasoning and Trade-offs

- **CloudFront as CDN:** Provides global delivery and HTTPS with WAF integration, improving security and performance, though it adds setup complexity.  
- **Private S3 bucket:** Ensures content is not publicly accessible, enforcing access only via CloudFront. Requires configuring Origin Access Control.  
- **AWS WAF:** Protects against common web attacks but introduces extra cost and management.  
- **CloudWatch:** Enables monitoring and logging for visibility into usage and security events.

## Challenges Faced

- Setting up CloudFront with private S3 origins and policies.  
- ACM certificate validation delays and DNS configuration.  
- Understanding WAF rule effects and tuning.

## What I Learned

- Best practices for securely hosting static websites on AWS.  
- Integration of AWS services for performance and security.  
- Importance of clear documentation and project structure.

