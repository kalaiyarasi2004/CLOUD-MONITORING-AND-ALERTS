# CLOUD-MONITORING-AND-ALERTS
#Company: CodTech IT Solutions
#Intern Name: KALAIYARASI S
#Intern ID: CT04DF2844
#Domain: Cloud Computing
#Duration: 4 Weeks
#Mentor: Neela Santosh

As part of my internship at CodTech IT Solutions, I worked on implementing cloud resource monitoring and automated alerting using Google Cloud Platform (GCP). The objective of this task was to gain practical experience in monitoring virtual machine (VM) resources, setting up alerting policies, and ensuring proactive incident response through GCP's integrated monitoring tools.

Project Overview:
I configured a custom monitoring alert policy for CPU usage of production VM instances. The system monitors CPU metrics in real-time, and automatically triggers alerts when defined thresholds are crossed.

The alert policy created was titled:
PROD-VM-CPU USAGE-ALERT
Key Components and Configuration

Monitoring Setup
Accessed GCP’s Operations Suite (formerly Stackdriver) under the Monitoring section.
Selected the Metrics Scope and associated VM instances for observation.

Alert Policy Configuration
Condition Type: VM Instance - CPU usage
Trigger Condition: Alert triggered when any time series crosses the threshold
Threshold Value: 0.1
Threshold Position: Above threshold
Retest Window: 2 minutes

Visual Dashboard and Graphs
Enabled visualization of CPU usage metrics over time.

Monitored usage across multiple instances:
instance-1
instance-2
instance-3
The graph displayed CPU usage trends and highlighted when metrics approached or exceeded the defined threshold.

Alerting and Notification (Optional Step)
(If configured) Set up notification channels via email or SMS for immediate response to alerts.
Ensured policy was enabled and actively monitoring in real-time.

Skills and Knowledge Gained
Google Cloud Monitoring:
Navigated GCP Monitoring dashboards
Created and tested alert policies for infrastructure health

Metric-Based Alerting:
Understood VM performance indicators
Applied threshold-based triggers for automated responses

Incident Management Awareness:
Learned proactive measures to detect and address resource bottlenecks
Gained insights into cloud infrastructure reliability

#OUTPUT

![Image](https://github.com/user-attachments/assets/14ed4696-81ed-4568-badf-fb24c0ebed3c)
