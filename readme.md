# AWS Resource Tracker

A simple **Bash script** to report AWS resource usage.  
This script uses the AWS CLI to fetch details of commonly used services.

## ✨ Features
- Lists all **S3 buckets**
- Lists all **EC2 instances**
- Lists all **Lambda functions**
- Lists all **IAM users**

## 🛠️ Prerequisites
- Install [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- Configure AWS credentials:
  ```bash
  aws configure
Bash shell (Git Bash or WSL on Windows, or Linux/macOS terminal)

🚀 Usage

Clone the repository and run the script:
'''bash aws_resource_tracker.sh'''
To save the output into a file:
'''bash aws_resource_tracker.sh > aws_report.txt'''

📂 Example Output

Here’s a sample run of the script (replace with your actual output):

Print list of S3 buckets

2025-08-28 12:00:00 my-test-bucket

Print list of EC2 instances

i-0abcd1234efgh5678  running

Print list of Lambda functions

my-lambda-function

Print list of IAM users

my-admin-user

💡 Note: This project is for learning purposes and can be extended to track more AWS services such as RDS, DynamoDB, or EKS.
