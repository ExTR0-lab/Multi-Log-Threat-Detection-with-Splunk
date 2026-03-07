# Project Overview

In this project, I successfully uploaded SSH log files to Splunk by following these steps:
Logged into the Splunk web interface.
Navigated to Settings > Add Data and selected Upload as the data input method.
Chose the prepared SSH log file for upload.
Set the appropriate Source Type.
Reviewed and configured settings like index, host, and sourcetype.
Submitted the upload and verified the SSH logs were successfully indexed and visible by running search queries in Splunk's interface.
![Screenshot 2024-12-03 054545](https://github.com/user-attachments/assets/26f2bb4c-dcae-4774-9ab8-bfc37c8c7cd7)
# Extract Relevant Fields
Identify key fields in SSH logs such as timestamps, source IP addresses, source Port, actions, etc.
![Screenshot 2024-12-03 054431](https://github.com/user-attachments/assets/b17bcbc5-1830-4146-841e-dbf9f3539afe)
#  Basic Search for SSH Logs
![Screenshot 2024-12-03 055259](https://github.com/user-attachments/assets/0b33e25b-ea0e-4bd0-8c6d-80ebc3887dd0)
                                # Detecting SSH Anomalies
# Brute-Force Detection
![Screenshot](https://github.com/user-attachments/assets/1cb7eefd-a1b7-4eef-8656-7a121d895268)
# Successful Logins After Many Failed Attempts
![sucessful login](https://github.com/user-attachments/assets/2fe527f0-010b-4861-94c6-ec219df67f75)
# Login to Uncommon User Accounts
![login ](https://github.com/user-attachments/assets/1ce7f159-b024-4911-9f16-892df3aa7e1d)
# Logins at Unusual Times
![time based anomaly](https://github.com/user-attachments/assets/7861dece-46a6-4eeb-a4b1-b3e8862b6370)
