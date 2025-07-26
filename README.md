# Packet-Captures


🕵️‍♂️ Wireshark Packet Capture & Analysis
🔍 Overview
A practical dive into network traffic analysis using Wireshark. This project highlights filtering, decoding, and identifying suspicious behavior in captured packets — essential for troubleshooting and security audits.
🎯 Key Objectives
- Capture traffic from targeted interfaces
- Filter and analyze HTTP, DNS, and TCP exchanges
- Spot anomalies (e.g. credential theft, spoofing)
- Document findings for audit purposes
🧰 Tools
| Tool | Function | 
| Wireshark | Packet capture & inspection | 
| tcpdump | (Optional) CLI capture layer | 
| Python | Post-capture parsing (if used) | 


📸 Example
Found decoded credentials in HTTP payload:
- Source IP: 192.168.1.105
- Payload: username=admin&password=letmein
🗂️ Structure
wireshark-analysis/
├── captures/
├── logs/
└── README.md


🚀 Next Steps
- Suricata rule-based traffic detection
- Integration with SIEM workflows


