# AWS API

## Story

AWS provides easy access to the services through the management console, but did you know that you could use a cli with AWS services? It is called AWS CLI. Let's try it with another AWS service - S3.

## What are you going to learn?

- How to create an IAM administrator user to avoid using the root user for daily tasks
- How to install and configure AWS CLI
- How to get started with Amazon Simple Storage Service (S3)
- How to create an S3 bucket both through the management console and through AWS CLI
- Manipulating S3 objects


## Tasks

1. Install AWS CLI for your OS and configure it with a newly created user.
    - Created a new user with administrator privileges.
    - AWS CLI configured with the new user.

2. Create an S3 bucket and upload a file (an image or for example an HTML "Hello World" page) using AWS CLI. Give the file public-read permissions. Check the URL of the file and try to load in your browser.
    - The uploaded file is publicly accessible through the browser.

3. Write an executable bash script that uses arguments (for example bucket name and region) to generate an S3 bucket.
    - S3 bucket generated with the script.

## General requirements

None

## Hints

- When creating a new user Write down the account ID (12 digits) because you will need it to log in the management console.
- After you login with the new account create an access key to use it with AWS CLI.
- Before creating a bucket with AWS CLI try creating it through the S3 management console.
- Try to understand what each option does when you are creating buckets/objects through the S3 management console or using `s3api`. Check the AWS documentation pages if you need additional information about an option.
- Be extremely careful about allowing public access to your buckets and the files you store in them. Be sure that you allow public access only when you really want to.
- Don't forget to cleanup after you finish your work.

## Background materials

- <i class="far fa-exclamation"></i> [Create an IAM user](https://docs.aws.amazon.com/AmazonS3/latest/gsg/SigningUpforS3.html#create-an-iam-user-gsg)
- <i class="far fa-exclamation"></i> [To get your access key ID and secret access key](https://docs.aws.amazon.com/powershell/latest/userguide/pstools-appendix-sign-up.html#get-access-keys)
- <i class="far fa-exclamation"></i> [Installing, updating, and uninstalling the AWS CLI version 2](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- <i class="far fa-exclamation"></i> [Configuration basics](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)
- <i class="far fa-exclamation"></i> [Amazon S3](https://aws.amazon.com/s3/)
- <i class="far fa-exclamation"></i> [Getting started with Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/gsg/GetStartedWithS3.html)
- <i class="far fa-exclamation"></i> [Setting up Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/gsg/SigningUpforS3.html)
- <i class="far fa-exclamation"></i> [Creating a bucket](https://docs.aws.amazon.com/AmazonS3/latest/gsg/CreatingABucket.html)
- <i class="far fa-exclamation"></i> [create-bucket](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/create-bucket.html)
- <i class="far fa-exclamation"></i> [s3api](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/index.html#cli-aws-s3api)


