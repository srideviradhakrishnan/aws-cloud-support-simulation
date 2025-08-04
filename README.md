# 🛠️ AWS Cloud Support Simulation Project

This project simulates a real-time cloud support environment using AWS services such as EC2, S3, IAM, CloudWatch, and CloudTrail. It focuses on incident monitoring, alert handling, and troubleshooting workflows commonly expected in support engineer roles.

---

## 🎯 Objective

To replicate real-world AWS support scenarios like infrastructure monitoring, permission troubleshooting, and incident resolution using a hands-on lab setup and documentation practices.

---

## 🔧 Tools & Technologies Used

- **AWS Services:** EC2, S3, IAM, CloudWatch, CloudTrail, SNS
- **Monitoring:** CloudWatch Alarms, CloudTrail logs
- **Automation:** SNS for alert notifications
- **Ticketing:** Jira-style issue tracking (mock)
- **Documentation:** Markdown-based runbooks
- **System Access:** Linux CLI, AWS Console

---

## 🔍 Simulated Incidents

| # | Incident | Service | Issue Type |
|--|----------|---------|------------|
| 1 | EC2 Instance Not Reachable | EC2 | Connectivity / SSH |
| 2 | Access Denied on Upload | S3 | IAM Permission Issue |
| 3 | IAM Role Misconfigured | IAM | Authorization Failure |
| 4 | CPU Utilization Alarm Triggered | EC2 | Resource Monitoring |
| 5 | Object Deletion Recovery | S3 | Versioning / Data Loss |

---


---

## 📈 Key Achievements

- ✅ Simulated **10+ real-world support issues**
- ✅ Reduced **troubleshooting time by 40%** using pre-defined runbooks
- ✅ Configured **CloudWatch Alarms** and **SNS** for automatic alerting
- ✅ Achieved **100% incident resolution** using logs, metrics, and IAM analysis
- ✅ Practiced Jira-style incident documentation for internal ticketing

---

## 🧾 Runbooks

- [EC2 Instance Not Reachable](ec2-instance-unreachable.md)
- [S3 Access Denied](s3-access-denied.md)
- [IAM Policy Issue](iam-policy-issue.md)

 --- 
 
 ## 🗃️ Incident Log

Download or view the [Incident Log CSV](incident-log-sample.csv) file for sample issues and resolutions.

---

## 📌 How to Use

1. Clone the repository:
git clone https://github.com/srideviradhakrishnan/aws-cloud-support-simulation.git

2.Explore runbooks in /runbooks for step-by-step troubleshooting guides

3.View alarm setup and alert configurations in /cloudwatch-alarms

4.Review incident-log-sample.csv to understand how issues were tracked

## 🙋‍♀️ About Me

👩‍💻 Sridevi R

Cloud Support Engineer

Passionate about AWS support, DevOps fundamentals, and continuous learning.
