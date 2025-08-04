# 🚨 Runbook: EC2 Instance Not Reachable

**Issue:** Unable to SSH into EC2 instance

## 🔎 Symptoms
- SSH timeout
- Instance status checks failing

## 🔍 Root Cause
- Security Group not allowing inbound traffic on port 22

## 🛠️ Resolution Steps
1. Go to the EC2 Dashboard → Instances → Select the affected instance.
2. Check **Security Groups** → Inbound Rules.
3. Add rule: Type = SSH, Port = 22, Source = My IP.
4. Save the rule and retry SSH.

## ✅ Verification
- SSH access restored
- Instance passes both status checks
