# Key Findings (Summary)

## TCP
- Observed TCP retransmissions and reviewed ACK/window behavior to evaluate possible packet loss causes.

## ARP
- Identified IP-to-MAC mapping changes and Wireshark warnings consistent with duplicate IP / potential ARP spoofing.

## DNS
- Observed domain-to-destination mismatches suggesting suspicious resolution behavior; validated normal resolution with comparison traffic.

## FTP
- Reconstructed FTP conversations in plaintext using Follow TCP Stream and recovered transferred artifacts to demonstrate insecure protocol exposure.
