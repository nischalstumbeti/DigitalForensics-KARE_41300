<table style="width:100%; font-family: Verdana, Tahoma; border: none;">
  <tr>
    <td align="left"><strong>Experiment No:</strong> 01</td>
    <td align="center"><h1>Wireshark: Network Packet Capture and Analysis</h1></td>
    <td align="right"><strong>Date:</strong> </td>
  </tr>
</table>

---

## Introduction

Wireshark is an open-source network protocol analyzer used for monitoring, capturing, and analyzing network traffic in real-time. It helps security professionals and forensic analysts understand communication patterns, detect anomalies, and investigate cybersecurity incidents.

---

## Objective

To capture and analyze network packets using **Wireshark** and understand its relevance in digital forensics and cybersecurity.

---

## Requirements

- Wireshark installed on the system
- Administrative privileges
- Basic understanding of TCP/IP protocols

---

## Installation Link

[Download Wireshark](https://www.wireshark.org/download.html)

---

## Procedure

1. **Install Wireshark**  
   - Download and install Wireshark from the official site.  
   - Install **WinPcap** or **Npcap** during installation for packet capturing.

2. **Run Wireshark as Administrator**  
   - Launch Wireshark with elevated privileges.

3. **Select Network Interface**  
   - Choose the correct network interface (Wi-Fi or Ethernet) to capture traffic.

4. **Start Capturing**  
   - Click the **shark fin icon** or press `Ctrl+E` to start capturing packets.

5. **Stop Capturing**  
   - Press `Ctrl+E` again to stop capturing.

6. **Apply Filters**  
   - Use filters like `http`, `ip.addr == 192.168.1.1`, or `tcp.port == 80` to analyze traffic.

7. **Analyze Packets**  
   - Expand packet details to view **Ethernet**, **IP**, **TCP/UDP**, and **Application Layer** data.

8. **Save Capture**  
   - Save the `.pcap` file for further forensic analysis.

---

## Sample Filters

| Filter Type           | Syntax Example                | Description                       |
|----------------------|-----------------------------|-----------------------------------|
| IP Address Filter    | `ip.addr == 192.168.1.1`    | Capture traffic from a specific IP |
| Port Filter          | `tcp.port == 443`           | Capture traffic on HTTPS port    |
| Protocol Filter      | `http`                      | Capture only HTTP packets        |

---

## Analysis

Wireshark provides deep visibility into network communications, helping investigators:  
- Identify suspicious connections  
- Detect unauthorized access attempts  
- Investigate malware communications  
- Export data for detailed forensic reporting  

---

## Conclusion

Wireshark is an essential tool for network forensics and cybersecurity investigations. It offers powerful features to capture, filter, and analyze network traffic efficiently.

---

## References

1. [Wireshark Official Documentation](https://www.wireshark.org/docs/)  
2. [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html_chunked/)


<div align="center" style="font-size:14px; font-family: Verdana, Tahoma; color:gray;">
This Expriment is Done by Nischal S Tumbeti - 99230041300 | 23S19 | CSE Department - SoC | KARE
</div>
