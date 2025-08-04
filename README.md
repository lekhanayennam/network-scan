# Task 1: Network Port Scanning and Traffic Capture
Basic Network Port Scanning and Traffic Capture using Nmap and Wireshark. This project involves scanning a local network to identify active devices and open ports using Nmap, and analyzing the traffic generated during the scan using Wireshark. Files include scan reports, packet capture, and IP configuration.

network-scan

Objective:
To perform a basic network scan using Nmap to discover devices and open ports within the local network and to analyze live traffic generated during the scan using Wireshark.

Tools Used:
-Nmap (for port scanning)
-Wireshark (for traffic analysis)

Steps Performed:

1. Nmap Scan
   Used the following command to scan the local network: nmap -sS 192.168.1.0/24 > scan.txt
2. Wireshark Packet Capture
   Started Wireshark and selected Wi-Fi interface.
   Captured packets while running the Nmap scan.
   Saved the packet capture as wireshark_pkt_capture.pcapng.
3. Nmap Scan
   Ran Nmap Scan after the packet capture: nmap -sS -v 192.168.1.0/24 > scan_2.txt

Files Included:

-scan_1.txt: Basic Nmap scan output
-scan_2.txt: Verbose and detailed scan
-wireshark_pkt_capture.pcapng: Packet capture during scan
-ip_configuration.png: Screenshot of IP configuration

What I Learned:

-How to use Nmap for port scanning within a private network
-Identifying devices and the services they expose
-How traffic looks in real-time using Wireshark
-Basics of analyzing network exposure and potential risks


Conclusion:

This task helped me gain foundational skills in network reconnaissance. I understood how to run TCP SYN scans with Nmap and use Wireshark to observe real-time packet traffic. These are essential skills in cybersecurity for identifying exposed services and evaluating network security.

Thank you!

