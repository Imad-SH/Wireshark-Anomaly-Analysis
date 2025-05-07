# Wireshark Anomaly Detection - Traffic Analysis Project

This project involves analyzing network traffic to detect and investigate anomalies such as suspicious file uploads, C2 communication, or malware behavior using Wireshark.

## 🔍 Goal
Detect anomalies in the provided PCAP, understand their nature, and document findings for educational and forensic purposes.

## 📁 Files
- `traffic.pcapng`: Captured traffic
- `analysis/`: Findings and screenshots
- `filters/`: Wireshark filters used
- `notes/`: Step-by-step log of the investigation

## 🛠️ Tools Used
- Wireshark
- Zeek (optional)
- Tshark (CLI)

## 🧠 Summary
Anomalies detected include:
- Suspicious POST request to `upload.php`
- File upload of `image.php.jpg` with reverse shell
- Beaconing behavior to external IP `117.11.88.124`

## 📸 Screenshots
See `analysis/screenshots/` folder.
