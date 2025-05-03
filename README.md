# IDS-using-Snort

## Objective
To install and configure Snort 3 (Snort++) on macOS as a network-based Intrusion Detection System (IDS). The projects goal is to monitor network traffic for any suspicious activity using custom rule sets, enhancing hands-on experience with cybersecurity monitoring and alerting tools.

### Skills Learned
- Installed and configured Snort 3 on macOS using Homebrew.
- Created and deployed custom Snort detection rules.
- Captured and analyzed network traffic for potential threats.
- Tested and validated alert generation using ICMP ping traffic.
- Interpreted Snort logs to verify rule effectiveness.
- Strengthened understanding of packet inspection and IDS fundamentals.

### Tools Used
- Homebrew (Package manager for installing Snort on macOS)
- Snort 3/Snort++ (IDS software for real-time traffic analysis)
- Ping utility (Used to generate ICMP traffic for testing detection)
- Text editor (Used to modify local.rules and Snort configuration files)

## Steps
- Installed Snort 3 via Homebrew on macOS.
- Created and configured the Snort configuration directory and rule files.
- Wrote a custom rule in local.rules to detect ICMP (ping) packets.
- Ran Snort in packet sniffing mode using the snort.lua configuration file.
- Initiated ICMP traffic by pinging external IPs (e.g., 8.8.8.8).
- Verified alerts in the terminal confirming rule-based detection of ICMP packets.
