Static Website Hosting on AWS

This project demonstrates static website hosting using Amazon Web Services (AWS). The website files are stored in an Amazon S3 bucket, which is configured to serve static content such as HTML, CSS, and JavaScript. By leveraging AWS's scalable and reliable infrastructure, the website is delivered quickly and efficiently to users.

Key Features:

Amazon S3: Used for storing and serving static website files.

Static Website Hosting: Enabled via S3 to handle HTTP requests directly.

Scalability: Automatically scales to handle traffic spikes without additional configuration.

Cost-Effective: Pay only for the storage and bandwidth you use.

Steps to Set Up Static Website Hosting on AWS with a GitHub Repository

1. Prepare Your GitHub Repository
Create a GitHub Repository: If you don’t already have one, create a new repository on GitHub.
Push Your Website Files: Ensure that your static website files (HTML, CSS, JavaScript) are pushed to the repository. Typically, you’ll have an index.html file as the entry point.

2. Create an S3 Buckek
Login to AWS Management Console: Go to the AWS Management Console and log in.
Navigate to S3: Go to S3 under Storage.

Create a New Bucket:
Click Create bucket.
Enter a unique name for your bucket.
Choose the AWS region closest to your target audience.
Leave other options as default or configure them based on your needs.
Click Create bucket.

3. Configure the S3 Bucket for Static Website Hosting
Enable Static Website Hosting:

Go to your bucket’s properties.
Click Properties and scroll down to Static website hosting.
Select Use this bucket to host a website.
Enter index.html for the Index document. Optionally, you can set an Error document if you have one.
Click Save changes.

Set Permissions:
Go to the Permissions tab of your bucket.
Click Bucket Policy and add a policy to make your bucket public
