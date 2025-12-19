# A Comprehensive Collection of Hands-on Ethical Hacking and Penetration Testing Labs
This repository is dedicated to providing step-by-step lab exercises and documentation for the entire lifecycle of ethical hacking and penetration testing.  It functions as both a personal portfolio and an instructional resource for learning the tools, methodologies, and critical thinking skills required to become a successful cybersecurity expert.
## IMPORTANT: Ethical & Legal Disclaimer
**This repository and its contents are strictly for educational and self-improvement purposes only.**

The concepts, tools, and techniques demonstrated in these labs are intended to be practiced in **controlled, permissioned environments** (e.g., local virtual machines, dedicated training platforms like Cisco's Networking Academy, TryHackMe/Hack The Box, or personal test networks).

* Please don't use any information, code, or techniques from this repository to target or compromise any system, network, or application that you do not explicitly own or have written, for which you do not have legal permission to test.

* Unauthorized access is illegal. We strongly condemn any illegal or malicious activity. The creator and contributors of this repository are not responsible for any misuse of the information I've included here.

* Always adhere to the Cyber Law and Rules of Engagement (ROE) in your respective jurisdiction.

**By cloning or using this repository, you agree to these terms.**

## [Phase 1: Pre-Engagement Activities](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-1-Pre-Engagement-Activities/ReadMe.md)
### Project 1: Creating Penetration Testing Agreement

A "Penetration Testing Agreement" is a contract that allows ethical hackers to test systems while keeping everyone protected. Basically, it tells what can be tested, when to do it, how to do it, and what to do with penetration testing.

This project showed that cybersecurity is not the same as just finding problems—it's about finding them in the right and professional way.

**sample_pentest_agreement:** [A Sample Penetration Testing Agreement](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/main/Sample-Penetration-Testing-Agreement-Shuseel.docx.pdf)

**What I learned:**
- As per cybersecurity requirements, legal frameworks are equally important regarding technical skills.
- Clear communication prevents further misunderstandings during security assessments. 
- Proper documentation itself protects both clients and security professionals.
- Researchers must surely set clear ethical limits before they start any testing work. 
- These boundaries should be established properly to ensure responsible research practices.


## [Phase 2: Reconnaissance, Information Gathering & Vulnerability Scanning](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-2-Reconnaissance-%26-Information-Gathering/ReadMe.md)

### Project 1: Performing Passive Reconnaissance

An information-gathering technique known as "passive reconnaissance" involves the tools not interacting directly with the target device or network.

**Lab 1: Using USINT Tools**

In this lab, I have explored several OSINT tools that are commonly used by pentesters. This includes the following:
* Examining the different OSINT resources
* Using SpiderFoot
* Investigating with Recon-ng
* Finding interesting files with Recon-ng

**Lab Documentation:** [Lab 1: Using USINT Tools](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-2-Reconnaissance-%26-Information-Gathering/Lab%20-%20Using%20OSINT%20Tools.pdf) 

### Project 2: Performing Active Reconnaissance

**Active reconnaissance** is a technique for obtaining information in which the instruments employed actually send enquiries to the target network or systems to elicit responses that are subsequently utilised to ascertain the network or system's condition.

**Lab 1: Enumeration with Nmap**

In this lab, I have learned the different types of Nmap scans and done a basic Nmap scan.

**Lab 2: Packet Crafting with Scrapy**

In this lab, I have learned how to investigate with the scapy tool, used scapy to sniff network traffic, create and send ICMP packets, and create and send TCP SYN packets.

**Lab 3: Network Sniffing with Wireshark**

In this lab, I have learned how to prepare the host to capture network traffic, capture and save network traffic, and view and analyze packet capture.

**Lab Documentation:** [Documentation of Lab 1, Lab 2, and Lab3](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-2-Reconnaissance-%26-Information-Gathering/Performing%20Active%20Reconnaissance%20with%20Nmap%20and%20Scapy.pdf)

Phase 3: Vulnerability Analysis
Lab 3.1: Service and Port Scanning

Tools Used: Advanced Nmap scripting (NSE) and version detection.

Objective: Identify running services and potential software vulnerabilities.

Lab 3.2: Automated Vulnerability Scanning

Tools Used: OpenVAS/Nessus (sample reports and configuration files).

Objective: Learn to analyze and prioritize scanner output.

Phase 4: Exploitation (Human & Client-Side)
Lab 4.3: Credential Harvesting with SET

Tools: SET (Social-Engineer Toolkit).

Objective: Clone a corporate portal to capture simulated user credentials via a phishing link.

Lab 4.4: Browser Hooking and Control with BeEF

Tools: BeEF, Kali Linux.

Objective: Demonstrate how a malicious script can "hook" a browser to execute commands and pivot into a private network.

(...  other projects will be listed here)


### **License**
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/main/License.md) file for details.

### **Contact & Support**
If you have questions, suggestions, or need clarification on a lab, please open an Issue in this repository.

Happy Hacking (Ethically!)!



