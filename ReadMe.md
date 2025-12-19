# Phase 3: Exploitation 

This repository is dedicated to providing step-by-step lab exercises and documentation for the entire lifecycle of ethical hacking and penetration testing.  It functions as both a personal portfolio and an instructional resource for learning the tools, methodologies, and critical thinking skills required to become a successful cybersecurity expert.
## IMPORTANT: Ethical & Legal Disclaimer
**This repository and its contents are strictly for educational and self-improvement purposes only.**

The concepts, tools, and techniques demonstrated in these labs are intended to be practiced in **controlled, permissioned environments** (e.g., local virtual machines, dedicated training platforms like Cisco's Networking Academy, TryHackMe/Hack The Box, or personal test networks).

* Please don't use any information, code, or techniques from this repository to target or compromise any system, network, or application that you do not explicitly own or have written, for which you do not have legal permission to test.

* Unauthorized access is illegal. We strongly condemn any illegal or malicious activity. The creator and contributors of this repository are not responsible for any misuse of the information I've included here.

* Always adhere to the Cyber Law and Rules of Engagement (ROE) in your respective jurisdiction.

**By cloning or using this repository, you agree to these terms.**

## Project 1: Performing Social Engineering Attacks With SET and BeEF

Social engineering involves influence, interrogation, and impersonation to gain information from victims without asking for it. A social engineering attack is a psychological manipulation technique used by cybercriminals to deceive people into giving up sensitive information or performing actions that compromise security.

**Tools used in this Lab:**
- Social Engineering Toolkit (SET) 
- Browser Exploitation Framework (BeEF)

**How are these tools used in real-world cybersecurity work?**
- Red Teams use Social Engineering Toolkit (SET) to create credential harvesting websites. It can also embed "payloads" into the documents to be sent via email.
- BeEF can be used to hook the target browser of a compromised user. Once hooked, the attacker has a command-and-control (C2) interface inside the user's browser.
 

**Lab 1: Exploring the Social Engineer Toolkit (SET)**

Social Engineering Toolkit (SET) can be used to launch numerous social engineering attacks. In this lab, I have learned to launch SET and explore the toolkit, clone a website to obtain user credentials, and capture and view user credentials. 

**Lab 2 - Using the Browser Exploitation Framework (BeEF)**

Browser Exploitation Framework (BeEF) is an application that runs in the browser, which allows taking control of target browsers that visit a malicious web page created by the attacker. In this lab, I have learned to load the BeEF GUI Environment and hook the local browser to simulate a Client-Side Attack and Investigate the different capabilities of BeEF exploitation. 

**Lab Documentation:** [**Documentation of Lab 1 and Lab 2**](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/b3812419e5293b889dc970ee955a402d43174b12/Module%204%20-%20Social%20Engineering%20Attacks%20with%20SET%20and%20BeEF.pdf)

## Project 2: Exploiting Network-based vulnerabilities Using enum4linux and Ettercap

**Network-based vulnerabilities** are weaknesses in a network's design, hardware, software, or human practices that attackers exploit for unauthorised access, data theft, or disruption, stemming from issues like unpatched systems, weak passwords, misconfigurations, insecure APIs, and social engineering, which require proactive patching, strong authentication, and segmentation to manage.

**Tools used in these labs:**
- Enum4linux
- Nmap 
- Ettercap
- Wireshark

**How are these tools used in real-world cybersecurity work?**
- Enum4linux can pull a list of users, share names, and group memberships without needing a password if the system is misconfigured.
- Ettercap can be used for ARP Poisoning and can also be used for capturing clear-text passwords.
- Nmap can be used for Network auditing and inventory, Vulnerability assessment, penetration testing reconnaisance, firewall testing, and incident detection.
- Wireshark can be used for network troubleshooting and viewing a "pcap" (packet capture) file for malware analysis. 

**Lab 1 - Scanning for SMB Vulnerabilities with enum4linux**

Enum4linux is a tool for enumerating information from Windows and Samba, which is an application that enables Linux and Apple clients to participate in Windows networks. With this lab, I have launched enum4linux and explored its capabilities, identified computers with SMB services running, used enum4linux to enumerate users and network file shares, and used smbclient to transfer files between systems.

**Lab 2 – Performing On-Path Attacks with Ettercap**

An **On-Path Attack**, also known as a **Man-in-the-Middle (MitM)** attack, happens when an attacker secretly positions themselves between two communicating devices, such as a user's browser and a web server, to intercept, eavesdrop on, or alter their data flow, often by manipulating DNS or hijacking sessions between them. Ettercap is used to perform on-path (MITM) attacks. With this lab, I have practiced a common form of on-path attack using a Kali tool and also launched Ettercap and Explored Its Capabilities, performed the On-Path (MITM) Attack, and used Wireshark to observe the ARP Spoofing Attack.

**Lab Documentation:** [**Documentation of Lab 1 and Lab 2**](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/b3812419e5293b889dc970ee955a402d43174b12/Module%205%20-%20Exploiting%20Network%20Based%20Vulnerabilities%20enum4linux%20and%20Ettercap.pdf)

(...  other projects will be listed here)


### **License**
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/main/License.md) file for details.

### **Contact & Support**
If you have questions, suggestions, or need clarification on a lab, please open an Issue in this repository.

Happy Hacking (Ethically!)!



