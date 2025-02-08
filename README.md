# Wireshark Network Traffic Analysis

## 📌 Overview
This project captures and analyzes network traffic using **Wireshark** to identify security vulnerabilities such as:
- **Unencrypted HTTP traffic**
- **DNS queries to third-party servers**
- **Protocol hierarchy breakdown**
- **Potential security risks**

## 📂 Files Included
- **[Wireshark_Network_Analysis_Report.pdf](./Wireshark_Network_Analysis_Report.pdf)** – Full security analysis report (detailed findings).
- **[network_capture.pcapng](./network_capture.pcapng)** – Main Wireshark capture file for analysis.
- **[1_Capture_Filter_Setup.png](./1_Capture_Filter_Setup.png)** – Screenshot of capture filter applied in Wireshark.
- **[1_Wireshark_Home.png](./1_Wireshark_Home.png)** – Screenshot of Wireshark home screen.
- **[Captured_Packet.png](./Captured_Packet.png)** – Screenshot of captured network packets.
- **[DNS_Traffic.png](./DNS_Traffic.png)** – Screenshot of captured DNS queries.
- **[HTTP_Traffic.png](./HTTP_Traffic.png)** – Screenshot of captured HTTP traffic.
- **[protocol_hierarchy.png](./protocol_hierarchy.png)** – Screenshot of protocol distribution in the capture.

## 🚀 How to Use This Project
1. **Download** [`network_capture.pcapng`](./network_capture.pcapng) **and open it in Wireshark**.
2. **Apply filters** such as:
   - `http` (to check unencrypted traffic)
   - `dns` (to analyze DNS queries)
   - `tls` (to view encrypted traffic)
3. Read the **full analysis in** [`Wireshark_Network_Analysis_Report.pdf`](./Wireshark_Network_Analysis_Report.pdf).

## 🔍 Next Steps
- Automate packet analysis with Python.
- Integrate findings into a SIEM tool (e.g., Splunk, ELK).
- Conduct real-world threat hunting exercises.

---
👤 **Author:** Iftekharul Islam  
📧 [Iftekharul.islamIT@gmail.com](mailto:Iftekharul.islamIT@gmail.com)
