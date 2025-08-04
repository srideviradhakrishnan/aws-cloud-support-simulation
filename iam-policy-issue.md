
# 🚨 Runbook: IAM Policy Issue (Permission Error)

**Issue:** User denied access to AWS service (e.g., EC2, S3)

## 🔎 Symptoms
- "AccessDenied" or "UnauthorizedOperation" in AWS Console/API

## 🔍 Root Cause
- IAM policy missing required actions or wrong resource scope

## 🛠️ Resolution Steps
1. Open the **IAM Policy Simulator**.
2. Simulate user actions to identify the failing permission.
3. Update IAM policy with correct permissions.
4. Validate scope (`*`, specific ARN) and conditions.

## ✅ Verification
- Task completes successfully (e.g., EC2 launch or S3 access)
