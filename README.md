# Deploying my Static Website using S3 and CloudFront

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [AWS Services Used](#aws-services-used)
4. [Steps to Deploy](#steps-to-deploy)
   - [Step 1: Set up an S3 Bucket](#step-1-set-up-an-s3-bucket)
   - [Step 2: Upload Website Files to S3](#step-2-upload-website-files-to-s3)
   - [Step 3: Configure S3 Bucket for Static Website Hosting](#step-3-configure-s3-bucket-for-static-website-hosting)
   - [Step 4: Create a CloudFront Distribution](#step-4-create-a-cloudfront-distribution)
   - [Step 5: Configure CloudFront Distribution](#step-5-configure-cloudfront-distribution)
5. [Testing](#testing)
6. [Troubleshooting](#troubleshooting)

## Introduction

This repository contains the documentation and necessary files to deploy my personal portfolio website on AWS using CloudFront and S3 buckets. The purpose of this project is to showcase my skills and provide a guide for deploying static websites on AWS.

## Prerequisites

- AWS account with appropriate permissions.
- AWS CLI installed and configured.
- Website files ready for deployment.

## AWS Services Used

- Amazon S3
- Amazon CloudFront

## Steps to Deploy

### Step 1: Set up an S3 Bucket

1.1. Open the AWS Management Console and navigate to the S3 service.

1.2. Create a new S3 bucket with a unique name.

### Step 2: Upload Website Files to S3

2.1. Use the AWS CLI or the AWS Management Console to upload your website files to the S3 bucket.

### Step 3: Configure S3 Bucket for Static Website Hosting

3.1. Enable static website hosting for the S3 bucket.

3.2. Set the index document and error document.

### Step 4: Create a CloudFront Distribution

4.1. Navigate to the CloudFront service in the AWS Management Console.

4.2. Create a new CloudFront distribution.

### Step 5: Configure CloudFront Distribution

5.1. Set the origin domain name to the S3 bucket's website endpoint.

5.2. Configure additional settings like default cache behavior and distribution settings.

## Testing

Verify that the website is accessible via the CloudFront distribution URL.

## Troubleshooting

If you encounter any issues during deployment, refer to the troubleshooting section in the documentation.

## References

Include links to AWS documentation and any other resources used during the implementation.

