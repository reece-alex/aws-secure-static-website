# website configuration

## S3 Bucket configuration

### Bucket overview
![S3 Bucket overview](https://github.com/reece-alex/aws-secure-static-website/blob/e8d358e479080c0038cf56cb3e023ad9b72d923d/images/Screenshot%202026-01-21%20105701.png)

 S3 bucket used to host the static website.Since im based in Cape Town i have chosen to host my S3 bucket in region Africa(Cape Town) Af-south-1 for lower latency.

 ### Bucket Permissions
 ![S3 bucket Permissions](https://github.com/reece-alex/aws-secure-static-website/blob/3ded2841f41e3de7ac6f35e733b11e6d069ca9f3/images/Screenshot%202026-01-21%20150519.png)


## CloudFront Distribution  
Overview of CloudFront distribution settings, including HTTPS enforcement.

![CloudFront Distribution](./cloudfront-distribution.png)

## ACM Certificate  
Details of the issued ACM certificate used for HTTPS.

![ACM Certificate](./acm-certificate.png)

## WAF Rules  
The AWS WAF Web ACL and its attached rules.

![WAF Rules](./waf-rules.png)

## CloudWatch Logs  
CloudWatch logs and metrics demonstrating monitoring setup.

![CloudWatch Logs](./cloudwatch-logs.png)
