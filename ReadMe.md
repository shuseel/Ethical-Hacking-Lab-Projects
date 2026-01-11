# Final Capstone Activity for Ethical Hacking Program by CISCO

## Introduction
This repository documents the completion of the Final Capstone Activity included within the Ethical Hacking program by CISCO, with the guidance of the instructors of ParoCyber. It's a hands-on penetration testing assessment modeled as a Capture The Flag (CTF) exercise. It functions as both a personal portfolio and an instructional resource for learning the tools, methodologies, and critical thinking skills required to become a successful cybersecurity expert.

## IMPORTANT: Ethical & Legal Disclaimer
**This repository and its contents are strictly for educational and self-improvement purposes only.**

The concepts, tools, and techniques demonstrated in these labs are intended to be practiced in **controlled, permissioned environments** (e.g., local virtual machines, dedicated training platforms like Cisco's Networking Academy, TryHackMe/Hack The Box, or personal test networks).

* Please don't use any information, code, or techniques from this repository to target or compromise any system, network, or application that you do not explicitly own or have written, for which you do not have legal permission to test.

* Unauthorized access is illegal. We strongly condemn any illegal or malicious activity. The creator and contributors of this repository are not responsible for any misuse of the information I've included here.

* Always adhere to the Cyber Law and Rules of Engagement (ROE) in your respective jurisdiction.

**By cloning or using this repository, you agree to these terms.**

## Objectives

The objectives of this Final Capstone Activity are to conduct a complete penetration test, starting with reconnaissance and then launching exploits against vulnerabilities. It also proposes the remediation for the exploits. This assessment was done in the form of a cybersecurity capture the flag exercise, which allows us to use our ethical hacking skills to locate files that contain flag values. In this project, we will use the tools to exploit vulnerabilities that were discovered while reaching the goal. 

The following are the main objectives of this assessment.

* Using SQL injection to find a flag file.
* Using web server vulnerabilities to investigate directories and find a flag file.
* Exploiting the open Samba shares to access a flag file.
* Analyzing a Wireshark capture file to find the location of a file containing flag information.

  **Target networks:**
  * Host: 10.5.5.0
  * Network: 192.168.0.0/24

## Tools Used
The following tools were used while conducting the assessement.
* Kali VM provided for the Ethical Hacker course
* DVWA
* Nmap
* smbclient
* Wireshark
* Web Browser Developer Tools

## Challenges Completed

### Challenge 1: SQL Injection
In this challenge, I have exploited a vulnerable web application to retrieve database credentials.
**Key steps performed:**
* Identifying injectable input fields
* Extracting user credentials via SQL Injection
* Cracking hashed passwords
* Using compromised credentials to access a protected system

### Challenge 2: Web Server Misconfiguration
In this challenge, I have exploited a directory listing that was enabled on the web server.
**Key steps performed:**
* Browsing exposed directories
* Locating sensitive files
* Retrieving the challenge flag
  
### Challenge 3: SMB Share Exploitation
In this challenge, I have scanned the internal network to discover the SMB services.
**Key steps performed:**
* Scanning the network for SMB services
* Enumerating anonymous shares
* Accessing the unsecured SMB directories
* Downloading and analyzing the flag files

### Challenge 4: PCAP Analysis
In this challenge, I have performed the network traffic analysis.
**Key steps performed:**
* Analyzing the captured network traffic using Wireshark
* Identifying the sensitive data transmitted in clear text
* Extracting the URLs, IP addresses, and exposed file contents
* Retrieving final challenge flag 

## Documentation

A complete documentation, including screenshots, processes, and steps from the preliminary setup, reconnaissance, exploitation, and finding the results by capturing the files.

**Documentation:** [**Documentation with Screenshots, Processes, and Steps**](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/22f8c067421ede7d995b7ae8ca96c628edd24eca/Final_Capstone_Activity__Instructor_Led__Student_version.pdf)


### **License**
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/shuseel/Ethical-Hacking-Lab-Projects/blob/main/License.md) file for details.

### **Contact & Support**
If you have questions, suggestions, or need clarification on a lab, please open an Issue in this repository.

Happy Hacking (Ethically!)!



