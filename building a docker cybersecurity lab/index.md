# Contents
---
## Introduction to Cybersecurity?

### What is Cybersecurity?

### Basic Concepts
* CIA Triad
* Access control models.  
  •	MAC (Mandatory Access Control). 
  •	DAC (Discretionary Access Control)
  •	RBAC (Role Based Access Control).
  •	Authentication, Authorization and Accounting
* Basic security policy
  * Least privilege.
  * Separation of duties
  * Defense in depth
  * Methods of authentication 
    * Password
    * Biometrics
    * Smart cards
    * Two-factor authentication
    * Multifactor authentication
### Risk = Vulnerability * Threat.

### Types of hackers
* Black hat
* White hat
* Grey hat
> Describe various techniques used by hackers to achieve intrusion.
Define social engineering and describe its role in cybersecurity.
Discuss common mechanisms that constitute social engineering (e.g., phishing, baiting, quid pro quo, pretexting).
Describe the variety of attacks targeting the human element.

### Types of attacks (e.g., active, passive).
*	Hardware
*	Software
*	Data
*	Network
Describe the tools and technologies used in cybersecurity.
Define intrusion detection and discuss its role in cybersecurity (e.g., HIDS and NIDS).
Explain what is meant by the term countermeasures (e.g., NIPS and HIPS).

### Business Continuity Plan
*	Risk assessment
  * Threat identification
  * Types of threats
  * Asset vulnerabilities
  * Threat sources.
*	Key Performance Indicators and Risk Measurement
  * Annualized loss expectancy (ALE)
  * Annual rate of occurrence (ARO)
  * Single loss expectancy (SLE)
  * Exposure Factor (EF).)

## Bulding a Docker Lab

A cybersecurity lab is a good way to learn the skills required to develop your offensive or defensive skills. This cybersecuirty lab provides a space that will emulate enterpises for the purpose of learning the basic skills required to understand the basics of enterprise attacks. These skills inculde networking, linux administration, linux scripting, hacker attack vectors and tools in a secure space. The lab supports a sceries of scenarrios that represent a simplified versions of various popular data breaches that occurred. To keep things interesting, the scenarios follow the development and growth of a small company, Jones Enterprises, as it grows from Joness Enterprises, Inc.

## Why Docker?

### What you will learn:

## Inital Lab Topology

### What you will learn:
* Attacker
* Metasploitable 2
## Next Level Lab Topology

### What will you learn:
* Wan
* Lan
* DMZ
* Firewall 

## Linux and penetration testing
### Basic skills developed
* Basic commands
* Nerwork commads
* Common ports and services
* IPv4 and IPv6 basic packet structure
* HTTP methods (GET and POST)
* DNS resolution
* SSL / TLS and certificates
* Common malware strategies (recon, exploit, callback)
* Knowledge of Transmission Control Protocol / Internet Protocol (TCP/IP) protocols
* Capturing network traffic
* Understanding basic firewall, IDS, IPS, DNS, DHCP, and security-concepts
* Scripting skills in any common language (Python, and Bash)

## Hacking the OSI Model

## Introduction to Penetration Testing Tools

> Penetration testing is the testing of the network, web application, and computer system to identify the security vulnerabilities that might get exploited by the attackers. It is also known as Pen testing. In many systems, the system vulnerabilities are referred to as Infra Vulnerability, and Application vulnerability is referred to as app vulnerability. This test can be performed manually and can be automated with software processor applications. In this article, we will learn the different types of Penetration Testing Tools. The purpose or primary goal of penetration testing is to identify the weak spots in the security of different systems and apps. It will also measure the compliance of security and test security issues. This test mainly performs once a year to ensure the security of the network and systems. Penetration test depends on various factors like the company’s size, the organization’s budgetn, and infrastructure.

## Phases of Penetration Testing
### Pre-Engagement
It’s a bad idea to hire a penetration tester and then let them run wild on your network. The pre-engagement phase consists of discussing and agreeing on scope, logistics, rules of engagement and timeline. Understanding what you want tested and why is important before entering discussions with vendors. There are many different types of penetration tests. Finally, rules of engagement are a formal contract between the tester and the organization receiving the test. Because many of the actions a penetration tester takes are illegal without explicit authorization, rules of engagement outline exactly what the tester is and isn’t allowed to do on your network. Any actions you don’t want taken need to be explicitly outlined in this contract (which will differ across organizations). It is also useful to list any critical assets in this contract to which the testers should pay extra attention. (https://builtin.com/cybersecurity/penetration-test)

### Recon
The reconnaissance phase consists of open-source intelligence (OSINT) gathering techniques to better understand the target organization and network. You’d be surprised what information you can freely gather from open sources. Attackers can gather network information using open-source tools such as Shodan or Censys. These tools continuously scan public-facing IP addresses and index their response headers. This allows the tester to begin building a picture of the external network without having to actively scan it.(https://builtin.com/cybersecurity/penetration-test)

### Discovery
The discovery phase consists of scanning and asset analysis. Typically, the tester will use a network scanning tool such as nmap to identify which assets are available and to gather some basic information about them such as operating system, open ports and running services. After getting the data and scanning the target, it is easy for an attacker to get access to exploit the target system. (https://builtin.com/cybersecurity/penetration-test)

### Vulnerability Analysis
After testers scan and analyze assets, they’ll use vulnerability identification methods to look for potential exploitation opportunities. Testers may identify vulnerabilities manually by analyzing the results of the previous discovery phase and utilizing existing knowledge, but they’re more likely to use an automated vulnerability scanning tool. There are many vulnerability scanning tools available, and they’re often used by organizations as part of a continuous vulnerability management program. Some popular tools include Tenable, Rapid7, and Qualys. Even nmap has some vulnerability scanning capabilities tests can use during the discovery phase.  (https://builtin.com/cybersecurity/penetration-test)

### Exploitation
After testers have identified vulnerabilities, attackers will attempt to exploit those vulnerabilities using either public or custom exploits. Generally, the ultimate target is root or administrator privileges on a machine, especially a domain controller. A common tool used for this is Metasploit, a framework that provides a streamlined process for finding and executing publicly available exploits for vulnerabilities. The exploitation phase is the key differentiator between a penetration test and a vulnerability scan. Vulnerability scans will identify vulnerabilities on the network, but can come with some caveats. They may identify false positives or exploit code that isn’t applicable to that individual environment. In a penetration test, however, the tester will exploit the vulnerability and prove that the vulnerability is actually exploitable, as well as simulate the ramifications of exploiting that machine — such as data exfiltration. For example, an asset may have been identified as low-risk due to the lack of sensitive information stored, transmitted or processed by the asset, but exploitable vulnerabilities proved to allow the attacker to pivot (move from one machine to another) through the network from that device.  (https://builtin.com/cybersecurity/penetration-test)

### Reporting
Reporting is arguably the most important phase of any penetration test. You’ll want to investigate the reporting standards of a vendor before moving forward with a test. One way to do this is by requesting a sanitized example report. During the reporting phase, the tester will put together a report outlining the test, including a narrative of the attack chains executed. A good penetration test report will have the findings well-organized and prioritized by risk level. They should provide screenshots and detailed descriptions so you can reproduce the issues during the remediation phase. Most testers will also provide guidance on how to remediate their findings.  (https://builtin.com/cybersecurity/penetration-test)

A typical penetration test report will consist of the following sections:
* Executive Summary
* Methodology
* Detailed Findings and Recommendations
* Appendices (usually including a vulnerability report in spreadsheet format)
 
### Remediation
The remediation phase is usually in the organization’s hands; it’s up to them what they do with  the findings and whether or not they close the identified gaps. 
Generally, an organization will take the penetration testing report and attempt to reproduce and validate the attack chains. Then, they’ll implement the appropriate changes using a combination of public sources, employee knowledge and the tester’s remediation guidance. While remediation may sound straightforward, it can be more difficult than you would think. Before making any domain-wide changes to the environment, it’s best to adopt a rollout testing process, starting with a small, diverse subset of test users or devices with documented and tested rollback procedures in the event the change breaks business processes.  (https://builtin.com/cybersecurity/penetration-test)

### Enumerating, Fingerprinting and Scanning tools
* Angry IP Scanner
* Telnet
* Hping3
* Netcat
* NMAP
* Nikto
* Wireshark
* SQLMap
* Dirbuster

### Automated tool
* metasploit

### Cracking tools
* Hydra
* John the Ripper

## Introduction to Web Attacks


