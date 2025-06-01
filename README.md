🔐 Firewall Configuration – UFW (Linux) & Windows Firewall

📘 Overview

This report covers practical steps to configure firewalls on both Linux systems using UFW (Uncomplicated Firewall) and Windows systems using Windows Defender Firewall. The focus is on demonstrating how to:

List existing firewall rules

Block a specific port (e.g., blocking Telnet on port 23)

Allow essential services (e.g., allow SSH port 22 in UFW)

Test firewall behavior using tools like telnet and netcat

Clean up by deleting firewall rules to restore system state

This exercise is ideal for those looking to understand how to configure UFW firewall on Linux and set up inbound/outbound rules in Windows Firewall.

🧑‍💻 What’s Included
🔹 Linux: UFW Firewall
On Linux, the UFW command-line firewall is used to:

View all active UFW rules using ufw status numbered

Deny TCP port 23 to block Telnet access

Allow port 22 to ensure SSH remains accessible

Verify firewall behavior using connection tests

Remove rules after testing to reset the firewall

These are basic UFW firewall commands that every system admin or cybersecurity student should know.

🔹 Windows: Windows Defender Firewall
On Windows, the Windows Firewall with Advanced Security GUI is used to:

List current inbound rules

Create a new rule to block Telnet (TCP port 23)

Test using telnet localhost 23 or other local tools

Allow or remove firewall rules using the GUI

This is a helpful exercise for anyone learning how to block a port in Windows Firewall or configure custom inbound/outbound firewall rules.

🧪 Testing Tools Used
telnet for Windows/Linux (to test blocked ports)

netcat (nc) on Linux (to listen or simulate port activity)

📖 Keywords Explained
This report answers many real-world questions like:

"How to use UFW firewall on Linux?"

"How to block a port using Windows Defender Firewall?"

"What UFW commands are used to deny and allow ports?"

"How to allow SSH in UFW?"

"How to test if a port is blocked using telnet or nc?"

These are common search queries from students, ethical hackers, and sysadmins working with host-based firewalls.

⚠️ Disclaimer
This report is intended for learning and educational purposes only.
All firewall configurations were performed in a controlled lab environment. Avoid experimenting on production machines unless fully aware of security risks and service disruptions.

🏁 Who Should Read This?
Beginners learning about Linux firewall configuration with UFW

Windows users curious about how to use Windows Defender Firewall to block ports

Students and professionals preparing for certifications like CEH, CompTIA Security+, etc.

Anyone interested in practical firewall security tutorial for beginners
