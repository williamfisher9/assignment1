# Assignment 1
## CloudFront URL:
http://d1a4yhspj3nthw.cloudfront.net/

## Bucket Static Website URL:
http://williamfisher-public-website-with-cloudfront.s3-website-us-east-1.amazonaws.com

## To copy the project to your local machine you can run the command:
```git clone git@github.com:williamfisher9/assignment1.git```

## Description:
#### This static website consists of 5 pages. Each of these page contains two videos, a logo, and a background image. The static web pages were uploaded to an S3 bucket which was turned public and then configured to host static website pages and then secured with an IAM policy, and finally, the contents were sped up using AWS CloudFront. 
#### Page 1
![ScreenShot](https://william-fisher-github-screenshots.s3.amazonaws.com/assignment1_screenshots/001.png)
#### Page 2
![ScreenShot](https://william-fisher-github-screenshots.s3.amazonaws.com/assignment1_screenshots/002.png)
#### Page 3
![ScreenShot](https://william-fisher-github-screenshots.s3.amazonaws.com/assignment1_screenshots/003.png)
#### Page 4
![ScreenShot](https://william-fisher-github-screenshots.s3.amazonaws.com/assignment1_screenshots/004.png)
#### Page 5
![ScreenShot](https://william-fisher-github-screenshots.s3.amazonaws.com/assignment1_screenshots/005.png)

## Project Setup:
1. Logint to AWS using your account.
2. Access S3 Service.
3. Create a new bucket and make it public then add an IAM policy to make the bucket accessible.
4. Upload the static web pages to the S3 bucket.
5. Enable "Host Static Website".
7. Access CloudFront service.
8. Create a distribution and select the S3 bucket as the origin for the CloudFront.
9. Create an OAI policy and update the bucket to provide access from CloudFront to S3 bucket.
