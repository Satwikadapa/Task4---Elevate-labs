# Task4---Elevate-labs
Setup and Use a Firewall on Windows



# Objective
The goal of this task is to configure and test basic firewall rules using Windows Defender Firewall. This involves blocking traffic on a specific port (Telnet - port 23), verifying the rule, and then removing it. The task enhances understanding of how firewalls filter and control network traffic.

---

##  Tools Used
- Windows Defender Firewall
- Telnet Client (for testing)
- Optional: PortQry / CMD / PowerShell

---

## Steps Performed

 1. Open Firewall Settings
- Accessed Windows Defender Firewall with Advanced Security through Control Panel.

 2. Viewed Current Rules
- Inspected existing inbound and outbound rules.

 3. Created a New Inbound Rule
- Blocked TCP port `23` (Telnet) to prevent unauthorized remote connections.

 4. Tested the Rule
- Verified the block by attempting a Telnet connection to port 23 — result: connection failed as expected.

 5. Removed the Block Rule
- Restored firewall to the original state by deleting the custom rule.


##  Learnings & Takeaways
- Understood how Windows Firewall filters network traffic using rule-based configurations.
- Gained hands-on experience in managing firewall rules.
- Realized the importance of blocking insecure protocols like Telnet (port 23).
- Learned how allowing and blocking specific ports helps improve overall system security.

- AUTHOR : SATWIK ADAPA
