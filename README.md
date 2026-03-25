# TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-Part-A

## Project File
[View Full Project PDF](https://github.com/Viney-Washington/TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-Part-A/blob/main/Viney%20Washington%20_%20Part%20A%20Target%20Attack%20Simulation%20Part%201.pdf)

## Overview
This project analyzes Advanced Persistent Threat (APT) activity within the BioGenX environment. The investigation began after malware was introduced due to an improperly verified digital signature, allowing unauthorized code to execute within the system.

## Objectives
- Identify APT tactics including command-and-control (C2) and persistence mechanisms  
- Analyze network traffic using Wireshark  
- Detect suspicious DNS and HTTP activity  
- Evaluate vulnerabilities that enabled the attack  
- Recommend mitigation strategies to reduce risk  

## Tools Used
- Wireshark  
- PCAP Traffic Analysis  

## Key Findings
- Repeated outbound connections to unfamiliar external domains  
- DNS queries to unknown domains indicating potential malicious communication  
- Persistent unencrypted HTTP traffic used to blend malicious activity with normal traffic  
- Indicators of command-and-control (C2) communication  
- Long-term communication patterns consistent with APT persistence behavior  

## Vulnerability Analysis
The root cause of the compromise was improper digital signature verification and reliance on manual validation processes. This allowed malicious software to bypass security controls and establish persistence within the environment.

## Recommendations
- Implement automated digital signature verification controls  
- Enforce encrypted communication protocols (HTTPS)  
- Strengthen outbound traffic monitoring and filtering  
- Apply least privilege access controls  
- Use automated security tools for continuous monitoring and validation  

## Conclusion
This project demonstrates how Advanced Persistent Threat actors use command-and-control communication and persistence mechanisms to maintain long-term access while avoiding detection. Strengthening automation, monitoring, and validation controls is essential to reducing risk and preventing future attacks.
