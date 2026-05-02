# AWS Static Website Hosting Architecture

## Project Overview
This project explains how to host a static website using AWS cloud services.

## Architecture Components

### Amazon S3
Used to store website files such as HTML, CSS, and images.

### Amazon CloudFront
Used as a Content Delivery Network (CDN) to deliver the website faster globally.

### Route 53
Used to connect a custom domain name to the website.

### AWS IAM
Used to manage permissions and secure access to AWS resources.

### HTTPS (SSL)
Ensures secure communication between users and the website.

## Architecture Flow
User → Route 53 → CloudFront → S3 → Website displayed

## Skills Demonstrated
- Cloud computing fundamentals
- AWS service understanding
- Static website hosting
- Cloud security basics
- Technical documentation
