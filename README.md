# CLI-CDN-Site
AWS CLI website - key, SG, EC2, S3, CloudFront

Create High Availability Architecture with AWS CLI

The architecture includes- 
- Webserver configured on EC2 Instance
- Document Root(/var/www/html) made persistent by mounting on EBS Block Device.
- Static objects used in code such as pictures stored in S3
- Setting up Content Delivery Network using CloudFront and using the origin domain as S3 bucket.
- Finally, place the Cloud Front URL on the web app code for security and low latency.


https://www.linkedin.com/pulse/website-infrastructure-purely-using-aws-cli-ec2-s3-github-singhal/
