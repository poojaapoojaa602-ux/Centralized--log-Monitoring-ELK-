 ## Centralized log Monitoring ELK
Centralized Log Monitoring and Threat Detection using ELK Stack
## Overview
This project implements centralized log monitoring and basic threat detection using the ELK Stack(Elasticsearch, Logstash, Kibana) stack. It helps in analyzing system logs and indetifying suspicious activities such as failed login attempts.
## Objectives
-Collect logs from multiple systems
-Centralized log storage
-Monitor logs in real time
-Detect suspicious activities like failed logins
## Architecture
Log Sources->Logstash->Elasticsearch->Kibana
##Tools Used
-Elasticsearch
-Logstash
-Kibana
## How it Works
-Logs are collected from system files orsample data
-logstash processes and filters logs
-Elasticsearch stores and indexes the logs
-Kibana visualizes the data using dashboards and charts
## Threat Detection
-Detects multiple failed login attempts from the same IP
-Idetifies suspicious or unknown IP addresses
-Monitors unusual traffic spickes
-Highlights repeated authentication failures 
## My Work
-Created sample log files to simulate system activity
-Analyzed failed login attempts and suspicious IPs
-Designed log views and dashboard representations
-Demonstrated basic threat detection using log patterns
## Screenshots 
### Kibana Dashboard
![Kibana Dashboard](https://github.com/user-attachments/assets/86d18db6-82a8-46fd-886b-593d59b988ed)
This dashboard visualizes logic attempts and overall system activity.

### Sample Logs File
![Sample Logs](https://github.com/user-attachments/assets/52e7ef44-9a04-42fb-9c69-422e0f940666)
This shows sample logs containing failed and successful login attempts with timestamps and IP addresses

### Discover logs
![Discover Logs](https://github.com/user-attachments/assets/a02c4b3e-f62a-48bb-96e2-2fa19563a808)
This view represents how logs are analyzed to identify suspicious patterns like repeated failed logins.

## Conclusion
This project shows how the ELK Stack can be used for centralized log monitoring and basic threat detection. It helps in identifying suspicious activities and improves system security awareness.







