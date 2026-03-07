In this project, I successfully uploaded FTP log files to Splunk by following these steps: Logged into the Splunk web interface. Navigated to Settings > Add Data and selected Upload as the data input method. Chose the prepared FTP log file for upload. Set the appropriate Source Type. Reviewed and configured settings like index, host, and sourcetype. Submitted the upload and verified the FTP logs were successfully indexed and visible by running search queries in Splunk's interface. And 
 # Extract Relevant Fields
Identify key fields in FTP logs such as  timestamp, session_id, source, source_type, src_ip, dst_ip, command, File Path/URL and others.
![a](https://github.com/user-attachments/assets/2bd56969-5c3a-4585-998a-04dce8b0eed8)
# All FTP login attempts
![b](https://github.com/user-attachments/assets/00059edc-9dcd-4c0d-bc59-c7b8e76b75df)
# All file transfers
![c](https://github.com/user-attachments/assets/4d79bf92-3523-4aa7-a126-fb67aa3272b8)
# large file transfer
![e](https://github.com/user-attachments/assets/76a4f6b7-1ee1-42f7-acf8-cdb68c478062)
# Failed attempt
![d](https://github.com/user-attachments/assets/ff49730c-e048-49c7-a8b2-c44a7c03a3fb)
# Detect multi_failed attempt By User
![f](https://github.com/user-attachments/assets/660c4321-fc33-4196-bb67-2aebf03cbb00)
#  Identifying Unusual Source IPs
![z](https://github.com/user-attachments/assets/edb81292-d1c2-4761-9978-4c2c875d44d1)
