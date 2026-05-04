🚀 AWS Cloud Cost Optimization – Identifying Stale Resources

🔹 Identifying Stale EBS Snapshots
📌 Description
This project implements an automated solution using AWS Lambda to identify and remove stale Amazon EBS snapshots that are no longer associated with any active EC2 instances, helping reduce unnecessary storage costs.

The Lambda function performs the following steps:
-Fetches all EBS snapshots owned by the account (self)
-Retrieves a list of active EC2 instances (both running and stopped)
-Checks whether each snapshot’s associated volume is attached to any active instance
-Identifies stale snapshots that are no longer in use
-Deletes unused snapshots to optimize storage utilization and reduce costs

⚙️ Key Features
-Automated detection of unused EBS snapshots
-Cross-referencing with active EC2 instances
-Cost optimization through cleanup of stale resources
-Serverless execution using AWS Lambda
-Scalable and efficient resource management

🛠️ Tech Stack
-AWS Lambda
-Boto3 (Python SDK for AWS)
-Amazon EC2
-Amazon CloudWatch

🎯 Outcome
-Reduced unnecessary storage costs
-Eliminated manual monitoring effort
-Improved cloud resource utilization
