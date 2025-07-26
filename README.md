# Packet-Captures

\
🕵️‍♂️ Wireshark Packet Capture & Analysis


\
🔍 Overview


A practical dive into network traffic analysis using Wireshark. This project highlights filtering, decoding, and identifying suspicious behavior in captured packets — essential for troubleshooting and security audits.

\
🎯 Key Objectives
- Capture traffic from targeted interfaces
- Filter and analyze HTTP, DNS, and TCP exchanges
- Spot anomalies (e.g. credential theft, spoofing)
- Document findings for audit purposes

\
🧰 Tools
| Tool | Function | 
| Wireshark | Packet capture & inspection | 
| tcpdump | (Optional) CLI capture layer | 
| Python | Post-capture parsing (if used) | 

\
📸 Example
Found decoded credentials in HTTP payload:
- Source IP: 192.168.1.105
- Payload: username=admin&password=letmein

\
🗂️ Structure
wireshark-analysis/
\
<img width="193" height="84" alt="image" src="https://github.com/user-attachments/assets/74247ad2-263d-4a33-af2f-02f0bcead9a0" />

\
\

🚀 Next Steps
- Suricata rule-based traffic detection
- Integration with SIEM workflows


