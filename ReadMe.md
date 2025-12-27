# Phase 2: Reconnaissance, Information Gathering & Vulnerability Analysis

## Project 1: Performing Passive Reconnaissance

An information-gathering technique known as "passive reconnaissance" involves the tools not interacting directly with the target device or network.

### **Lab 1: Using USINT Tools**

In this lab, I have explored several OSINT tools that are commonly used by pentesters. This includes the following:
* Examining the different OSINT resources
* Using SpiderFoot
* Investigating with Recon-ng
* Finding interesting files with Recon-ng

**Lab Documentation:** [Lab 1: Using USINT Tools](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-2-Reconnaissance-%26-Information-Gathering/Lab%20-%20Using%20OSINT%20Tools.pdf) 

## Project 2: Performing Active Reconnaissance

**Active reconnaissance** is a technique for obtaining information in which the instruments employed actually send enquiries to the target network or systems to elicit responses that are subsequently utilised to ascertain the network or system's condition.

### **Lab 1: Enumeration with Nmap**

In this lab, I learned about the different types of Nmap scans and performed a basic Nmap scan.

### **Lab 2: Packet Crafting with Scrapy**

In this lab, I learned how to investigate using the Scapy tool, including sniffing network traffic, creating and sending ICMP packets, and creating and sending TCP SYN packets.

### **Lab 3: Network Sniffing with Wireshark**

In this lab, I have learned how to prepare the host to capture network traffic, capture and save network traffic, and view and analyze packet capture.

**Lab Documentation:** [Documentation of Lab 1, Lab 2, and Lab3](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/Phase-2-Reconnaissance-%26-Information-Gathering/Performing%20Active%20Reconnaissance%20with%20Nmap%20and%20Scapy.pdf)

## Project 3: Website Vulnerability Scanning with Nikto and GVM

Website vulnerability scanning is an automated process that systematically examines a website or web application to identify security issues, technical flaws, or misconfigurations.

### **Lab 1: Website Vulnerability Scanning Nitkto**

Nikto is a command-line, open-source tool created especially to identify web server vulnerabilities. It is well-known for being "noisy"—it doesn't attempt to conceal its presence, which makes it a great tool for determining whether your security measures, such as an intrusion detection system, are truly operational.

**Objectives**
In this lab, we will complete the following objectives:
* Launching and Performing a Basic Scan with Nikto
* Scanning Multiple Web Servers Using Nitko
*	Investigating the Website Vulnerabilities
*	Exporting Nikto Results to a File

**Tools used**
* Nikto 
* National Vulnerability Database (https://nvd.nist.gov)

 **Uses in the real-world cybersecurity work**
 * Nikto tool is often used as the first "noisy" scanning tool for vulnerability scanning of a web application. In a real-world engagement, we use this tool to test if a client's Intrusion Detection System (IDS) is actually working or not.
 * When the vulnerability scanning tool, such as GVM or Nikto, tells a server has a "CVE-2024-XXXX" vulnerability, we use the NVD to understand the impact of this vulnerability and to look up the Common Vulnerability Scoring System (CVSS) score.

### **Lab 2: Website Vulnerability Scanning GVM**

Greenbone Vulnerability Management (GVM), formerly known as OpenVAS, is a large, enterprise-level network vulnerability management system. It has a collection of services that collaborate to scan thousands of devices on a network with advanced features, in contrast to the lightweight Nikto.

**Objectives**
In this lab, we will complete the following objectives:
* Scanning a Host for finding the Vulnerabilities

**Tools used**
* Greenbone Vulnerability Management (GVM)

**Uses in the real-world cybersecurity work**
* This tool is used by large organizations to perform Internal Vulnerability Assessments. GVM scans every IP address on the network—printers, laptops, servers, and IoT devices—to find its vulnerabilities. 

 ### **Documentation of Lab 1 and Lab 2**
 
 Here is the Lab Documentation of Lab 1 and Lab 2 with Key commands, payloads, and Screenshots:

[**Documentation of Lab 1 and Lab 2**](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/f34c5f2eb7d5d62df29dbcc10fdf7c0ddfdfed18/Module%206%20-%20Website%20Vulnerability%20Scanning.pdf)


(...  other projects will be listed here)


### **License**
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/main/License.md) file for details.

### **Contact & Support**
If you have questions, suggestions, or need clarification on a lab, please open an Issue in this repository.

Happy Hacking (Ethically!)!



