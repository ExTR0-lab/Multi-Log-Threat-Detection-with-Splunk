Welcome to the Multi-Log-Threat-Detection-with-Splunk Project, where I explore the power of Splunk Enterprise for analyzing network and system logs. This project demonstrates how log data from multiple protocols—HTTP, SSH, SMTP, FTP, and DNS—can be ingested, analyzed, and visualized to provide actionable insights for network monitoring, security analysis, and troubleshooting.

A key focus of this project is detecting potential data exfiltration via DNS traffic, a common technique used by attackers to transfer sensitive data covertly from internal networks.

Protocols Analyzed

HTTP (Hypertext Transfer Protocol): Analyze web traffic logs to monitor requests, detect errors, and understand user behavior patterns.

SSH (Secure Shell): Investigate login attempts to detect brute-force attacks and unauthorized access.

SMTP (Simple Mail Transfer Protocol): Examine mail server logs for suspicious email activity, spam, or delivery issues.

FTP (File Transfer Protocol): Assess file transfer patterns to detect unauthorized access or potential data leaks.

DNS (Domain Name System): Inspect DNS query logs to detect abnormal traffic patterns and DNS-based exfiltration attempts, such as long or encoded queries to attacker-controlled domains.

Key Features and Achievements
Real-Time Monitoring and Visualization

Instant Insights: Monitor network and system activity in real time to quickly detect abnormal behavior.

Comprehensive Dashboards: Custom dashboards provide clear visualization of metrics and trends across multiple protocols.

Security Monitoring and Threat Detection

SSH Login Analysis: Detect unusual login attempts, failed logins, and brute-force attack patterns.

SMTP Monitoring: Identify unauthorized mail flows, spam, or phishing activity.

DNS Security: Detect potential DNS-based attacks, including suspicious query patterns and possible data exfiltration attempts.

Performance Monitoring and Optimization

HTTP Traffic Analysis: Monitor web service performance, error rates, and slow responses.

FTP Usage Monitoring: Detect unauthorized or unusual file transfers and prevent data leaks.

Data Aggregation and Search

Unified Log Collection: Collect logs from multiple sources into a single platform for easier analysis.

Custom SPL Queries: Write targeted queries to pinpoint anomalies or investigate specific security incidents.

Alerting and Automated Monitoring

Proactive Alerts: Configure automated notifications for failed logins, high error rates, or suspicious DNS queries.

Anomaly Detection: Detect unusual behavior without manual intervention using thresholds and alerts.

Troubleshooting and Root Cause Analysis

Quickly identify and correlate issues across multiple protocols, such as connecting a DNS anomaly to a related HTTP or FTP failure.

Security and Compliance

Maintain audit trails for forensic investigation and ensure adherence to security policies.

Enable proactive monitoring and incident response to reduce potential damage from attacks.

Detecting Data Exfiltration Through DNS Log Analysis

A core component of this project is detecting DNS-based data exfiltration, where attackers encode data into DNS queries to bypass security monitoring.

Investigation Steps:

Identify Source IPs Generating DNS Traffic
Determine which internal hosts are making the highest number of DNS requests.

Identify Queried Domains
Look for communication with unknown or suspicious domains controlled by attackers.

Detect Long or Encoded DNS Queries
Long, random-looking subdomains often indicate data encoded for exfiltration.

Measure Scale of Suspicious Activity
Count the number of abnormal DNS requests to estimate potential exfiltration.

Using these steps, I identified 315 suspicious DNS queries, many targeting domains such as tunnelcorp.net, consistent with potential DNS tunneling activity.

Skills Developed

Splunk Proficiency: Data ingestion, SPL query writing, dashboards, and alert configuration.

Log Parsing & Normalization: Transform raw logs into structured formats for analysis.

Threat Detection & Troubleshooting: Hands-on experience in identifying abnormal behavior and investigating security incidents.

Data-Driven Decision Making: Use log insights to optimize system performance and security posture.

Technologies Used

Splunk Enterprise: Central platform for collecting, indexing, and analyzing log data.

Search Processing Language (SPL): Query and manipulate log data for investigation.

Data Visualization: Build interactive dashboards for insights and reporting.

What This Project Demonstrates

Real-time network and system monitoring.

Detection of potential security threats, including DNS-based exfiltration.

Optimized network and system performance through log analysis.

Enhanced incident response with automated alerts and detailed dashboards.

Strong hands-on experience for a career in SOC analysis, network security, or data analysis.
