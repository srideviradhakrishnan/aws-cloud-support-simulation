# 🚨 Runbook: Access Denied When Uploading to S3

**Issue:** IAM user unable to upload objects to S3 bucket

## 🔎 Symptoms
- "AccessDenied" error when calling `PutObject`

## 🔍 Root Cause
- Missing `s3:PutObject` permission

## 🛠️ Resolution Steps
1. Identify the IAM role/user.
2. Check their **attached policy** using IAM Console.
3. Add the required permissions:
```json
{
  "Effect": "Allow",
  "Action": "s3:PutObject",
  "Resource": "arn:aws:s3:::bucket-name/*"
}
