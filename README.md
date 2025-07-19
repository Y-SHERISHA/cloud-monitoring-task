**CODETECH TASK2 – CLOUD MONITORING SETUP**
NAME: Y. Sherisha
TASK: Set up Monitoring for a Cloud-Based Application
PLATFORM USED: Amazon Web Services (AWS) – CloudWatch

Instance Details
Instance ID: i-05f55a015dd7a6470

Instance Name: codetech24

Public IP: 13.204.53.172

Steps Performed
**1. Created an EC2 Instance**
Launched an EC2 instance using Amazon Linux 2

Instance type: t2.micro

Enabled HTTP and SSH access in the security group

Verified that the instance was successfully launched

**2. Enabled Cloud Monitoring**
Verified that EC2 monitoring was enabled

Metrics such as CPUUtilization and DiskReadOps were visible in CloudWatch

**3. Created CloudWatch Dashboard**
Built a custom CloudWatch dashboard

Added key widgets: CPUUtilization, NetworkIn, NetworkOut

Configured charts with real-time data streaming

**4. Configured Alarm for CPUUtilization**
Alarm created for the EC2 instance using CPUUtilization metric

Condition: If CPU usage >= 70% for 1 data point over 5 minutes

Alarm action: send notification (optional)

**5. Verified Metrics and Alarm States**
Simulated CPU load

Verified that alarm transitioned to ALARM state during threshold breach

Validated that dashboard updated in real-time

**Result**
✅ Successfully configured CloudWatch to monitor an EC2 instance.
✅ Alarm transitioned to ALARM state when CPUUtilization crossed the defined threshold.
✅ Real-time metrics visualized via dashboard.
