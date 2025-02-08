{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww28600\viewh18000\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Wireshark Network Traffic Analysis\
\
## \uc0\u55357 \u56524  Overview\
This project captures and analyzes network traffic using **Wireshark** to identify security vulnerabilities such as:\
- **Unencrypted HTTP traffic**\
- **DNS queries to third-party servers**\
- **Protocol hierarchy breakdown**\
- **Potential security risks**\
\
## \uc0\u55357 \u56514  Files Included\
- **[Wireshark_Network_Analysis_Report.pdf](./Wireshark_Network_Analysis_Report.pdf)** \'96 Full security analysis report (detailed findings).\
- **[network_capture.pcapng](./network_capture.pcapng)** \'96 Main Wireshark capture file for analysis.\
- **[1_Capture_Filter_Setup.png](./1_Capture_Filter_Setup.png)** \'96 Screenshot of capture filter applied in Wireshark.\
- **[1_Wireshark_Home.png](./1_Wireshark_Home.png)** \'96 Screenshot of Wireshark home screen.\
- **[Captured_Packet.png](./Captured_Packet.png)** \'96 Screenshot of captured network packets.\
- **[DNS_Traffic.png](./DNS_Traffic.png)** \'96 Screenshot of captured DNS queries.\
- **[HTTP_Traffic.png](./HTTP_Traffic.png)** \'96 Screenshot of captured HTTP traffic.\
- **[protocol_hierarchy.png](./protocol_hierarchy.png)** \'96 Screenshot of protocol distribution in the capture.\
\
## \uc0\u55357 \u56960  How to Use This Project\
1. **Download** [`network_capture.pcapng`](./network_capture.pcapng) **and open it in Wireshark**.\
2. **Apply filters** such as:\
   - `http` (to check unencrypted traffic)\
   - `dns` (to analyze DNS queries)\
   - `tls` (to view encrypted traffic)\
3. Read the **full analysis in** [`Wireshark_Network_Analysis_Report.pdf`](./Wireshark_Network_Analysis_Report.pdf).\
\
## \uc0\u55357 \u56589  Next Steps\
- Automate packet analysis with Python.\
- Integrate findings into a SIEM tool (e.g., Splunk, ELK).\
- Conduct real-world threat hunting exercises.\
\
---\
\uc0\u55357 \u56420  **Author:** Iftekharul Islam  \
\uc0\u55357 \u56551  [Iftekharul.islamIT@gmail.com](mailto:Iftekharul.islamIT@gmail.com)\
}