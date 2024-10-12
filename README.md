# PredictiveNmap

<br>This is a nmap script that works by predicting the ports on the remote target.</br>

<br>File System structure shown in the image below:</br>
![PredictiveNmap](https://github.com/user-attachments/assets/5de35d71-e5df-4a41-b2c1-91c751bb3105)

<br>Terminal output shown in the image below:</br>
![Nmap](https://github.com/user-attachments/assets/ee927cff-ba72-4997-8a07-7b7ef8db5425)

## New Features
- Custom Port Range Scanning: Allow the user to specify a port range via input
- Port Status (Open/Closed): Log whether each port is open or closed, not just a prediction score
- Scan Multiple IPs: Allow scanning of multiple IPs provided by the user</br>
- Historical Tracking: Store historical data for each IP and port, allowing for more intelligent predictions based on past results
- Error Handling and Logging: Log errors and details of failed scans or unreachable IPs to a separate log file
- Summary Report: After the scan completes, print a summary with the number of open and closed ports for each IP
