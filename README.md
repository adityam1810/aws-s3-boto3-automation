# AWS S3 Automation with Python & Boto3

A simple AWS automation project that uses Python and Boto3 to interact with Amazon S3.

## Features

- Connect to AWS S3 using Boto3
- Create an S3 bucket programmatically
- Specify the AWS region
- List available S3 buckets
- Practice AWS SDK automation using Python

## Technologies

- Python
- AWS S3
- AWS IAM
- Boto3
- AWS CLI

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd aws-s3-boto3-automation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Configure AWS Credentials

Configure AWS CLI before running the script:

```bash
aws configure
```

Provide your:

- AWS Access Key ID
- AWS Secret Access Key
- Default AWS region
- Output format

> Never commit AWS access keys or secret keys to GitHub.

## Run

```bash
python s3_bucket.py
```
#Here is the backup

<img width="1366" height="542" alt="Screenshot (356)" src="https://github.com/user-attachments/assets/b9f2ef79-87df-471b-9e1b-6de79cd7fa10" />

## What I Learned

Through this project, I practiced:

- Using the AWS SDK for Python (Boto3)
- Creating S3 resources programmatically
- Working with AWS regions
- IAM permissions for S3
- Listing AWS S3 buckets
- Troubleshooting AWS authorization and S3 bucket naming errors

## Future Improvements

- Upload backup files to S3
- Download objects from S3
- Automatically create local backups
- Add timestamp-based backup names
- Add error handling
- Implement backup retention
- Apply IAM least-privilege permissions
