# 🛡️ Real-Time Network Security Monitoring Dashboard (SOC)

A high-performance Security Operations Center (SOC) dashboard built using **Splunk Enterprise** to monitor and analyze over **2.6 million network events** in real-time. This project visualizes live traffic patterns, protocol distributions, and network intensity.

---

## 🚀 Key Features

* **🚨 Live Traffic Intensity:** Dynamic single-value monitor that changes color based on load (Green/Orange/Red).
* **📊 Protocol Breakdown:** Real-time analysis of SSDP, QUIC, TLS, and other network protocols.
* **🔍 Endpoint Tracking:** Identifying top internal talkers and external traffic destinations.
* **🌑 Dark Mode Optimized:** Designed for a professional "War-Room" experience.

---

## 📸 Dashboard Preview & Analysis

### 1. Main SOC Dashboard Overview
This is the complete view of the monitoring system, showing all critical metrics at a glance.
![Main Dashboard](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/1.png)

### 2. Live Network Intensity (Real-time Alerts)
Our dynamic alerting system. It monitors packet flow and changes color automatically:
* **Green:** Normal Traffic
* **Red:** High Intensity / Potential Spike
![Traffic Intensity](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/6.png)

### 3. Protocol Distribution (Pie Chart)
Visualizing the diversity of network protocols currently active in the environment.
![Protocol Breakdown](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/5.png)
![Protocol Stats](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/2.png)

### 4. Top Endpoint Communications
Tracking which internal devices are generating the most traffic and their destinations.
![Top Talkers](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/3.png)
![Destinations](https://raw.githubusercontent.com/AmalUBasnayake/Splunk-Realtime-Network-SOC-Dashboard/main/4.png)

---

## 🛠️ Technical Stack
* **SIEM Tool:** Splunk Enterprise
* **Packet Capture:** TShark (Wireshark CLI)
* **Data Format:** CSV-based live log feed
* **Language:** Splunk Search Processing Language (SPL)

---

## 💡 How it Works
1.  **Capture:** TShark captures live network packets and exports them to a structured CSV.
2.  **Ingest:** Splunk monitors the CSV file in real-time.
3.  **Visualize:** SPL queries transform raw logs into the visual components shown above.

---
**Developed by [Your Name/Handle]** 🚀
