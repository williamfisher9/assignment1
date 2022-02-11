# Assignment 1
## CloudFront URL:
http://d1a4yhspj3nthw.cloudfront.net/

## Bucket Static Website URL:
http://williamfisher-public-website-with-cloudfront.s3-website-us-east-1.amazonaws.com

## To copy the project to your local machine you can run the command:
```git clone williamfisher9:assignment1```

## Description:
A static website was deployed to AWS by following the below steps:
1. You will create a public S3 bucket
2. esign and upload the website files to your bucket. The website should at least include one image, one short video (Maximum 30 Seconds), and 5 pages.  
3. You will configure the bucket for website hosting and secure it using IAM policies.
4. You will speed up content delivery using AWS’s content distribution network service or CloudFront.
5. Create a GitHub Repository for assignment 1, submit all the site content to this repository. 
6. Develop effective technical documentation for assignment 1 - Create a REAME.md markdown descripting the details of your AWS EC2 infrastructure deployment for hosting your website. Including the link of your website.

## Project Setup:
1. Logint to AWS using your account.
2. Access S3 Service.
3. Create a new bucket and make it public then add a policy to make the bucket accessible.
4. Change the bucket to static website.
5. Access CloudFront service.
6. Create a distribution and select the S3 bucket as the origin for the CloudFront.
7. Create an OAI policy and update the bucket bucket to provide access from CloudFront to S3 bucket.