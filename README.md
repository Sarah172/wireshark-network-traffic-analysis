# Wireshark Network Traffic Analysis & Protocol Investigation
Packet capture analysis performed in Wireshark to identify network performance issues and security indicators across TCP, ARP, DNS, and FTP traffic.

## Tools
- Wireshark
- TCP/IP, DNS, ARP, FTP protocol analysis

## Key Skills Demonstrated
- TCP retransmission analysis and flow review
- ARP spoofing indicator detection (IP-to-MAC anomalies / duplicate IP)
- DNS anomaly investigation and validation against normal resolution behavior
- FTP stream reconstruction and artifact recovery (plaintext protocol risk)

## Project Summary
This investigation analyzed multiple packet captures to:
1. Diagnose TCP performance issues by isolating retransmissions and inspecting windowing behavior.
2. Identify ARP behavior consistent with spoofing (changing IP-to-MAC mapping and duplicate IP warnings).
3. Investigate DNS/HTTP traffic for suspicious resolution behavior and compare against normal DNS responses.
4. Reconstruct FTP sessions using Follow TCP Stream and export artifacts to demonstrate the risks of unencrypted protocols.

## Deliverables
- Report: `report/Wireshark_Lab_Report.pdf`

## Notes
This work was completed in a controlled lab environment using training packet captures.
No proprietary or sensitive production traffic is included in this repository.
