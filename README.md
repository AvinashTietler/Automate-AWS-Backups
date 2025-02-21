# Automate-AWS-Backups
Automate AWS Backups using AWS CLI, Lambda, S3, and EBS Snapshots

# 📌  Overview

Data backup and recovery are critical aspects of cloud infrastructure. This project demonstrates how to automate AWS backups using AWS Lambda, AWS CLI, S3, and EBS Snapshots. The automation ensures that EC2 volumes are backed up periodically, and older backups are managed efficiently using lifecycle policies.

# 🎯 Objectives

1. Create automated backups of EC2 instances using EBS Snapshots.

2. Store logs and backup metadata in an S3 bucket.

3. Schedule backups using AWS Lambda and CloudWatch Events.

4. Implement snapshot retention policies to delete old snapshots.

# 🛠 Tech Stack

AWS Lambda

Amazon S3 (Storing backup logs)

Amazon EC2 (EBS Snapshots)

AWS CLI (For testing and manual operations)

IAM Roles & Policies (For access control)

# 🏗 Project Setup

We need to perform these actions in given order:

1️⃣ IAM Role for Lambda Execution - Create Role and Assign Necessary Policies

2️⃣ Create an S3 Bucket for Backup Logs

3️⃣ Create AWS Lambda Function for Backup Automation

4️⃣ Deploy Lambda Function

5️⃣ Schedule Lambda Function using CloudWatch Events

6️⃣ Implement Snapshot Retention Policy (Deletes Snapshots Older than 7 Days)

# 📊 Expected Outcome

✅ Automated daily EBS backups of EC2 instances with a Backup: true tag.

✅ Snapshot retention policy removes backups older than 7 days.

✅ Logs stored in S3 for backup history tracking.

✅ Serverless and cost-effective solution with AWS Lambda.

