# Wazuh Home-Lab

## ℹ️Overview

Wazuh is an open-source security monitoring platform used for threat detection, integrity monitoring, and incident response. Setting up a Wazuh home lab environment is an excellent way for SOC (Security Operations Center) analysts to gain hands-on experience in security monitoring, alerting, and response.  
![Blue Sand White Beach Simple Watercolor Etsy Shop Banner (7)](https://github.com/0xrajneesh/Wazuh-Home-Lab/assets/40385860/651c105c-0f5b-4eda-ac51-3b52e33b2374)

This Home-Lab covers:


## 🧮Requirements

- **Hardware**:
  - Computer with at least 16GB RAM and dual-core processor
- **VM/ISO Image**:
  - Wazuh OVA Image
  - Windows 10 Machine OVA image
  - Ubuntu Server 22.04 Image
  - Kali Linux(Attacker Machine) OVA image

## 🖼️Lab Diagram

![Home-Lab (4)](https://github.com/0xrajneesh/Home-Lab/assets/40385860/a9d12473-c560-45b5-be95-e6d4dad597ec)


## What will you learn?
In the Wazuh Home-Lab, you'll gain hands-on experience in:

- Threat detection for various cyber threats
- Incident response to security breaches
- System integrity monitoring
- Behavior analysis for identifying anomalies
- Setting up and configuring Wazuh agents
- Analyzing and responding to failed SSH logins
- Detecting unauthorized access to sensitive files
- Monitoring and alerting on executable file modifications
- Identifying anomalous network traffic patterns
- Recognizing unusual account activities
- Notifying and responding to security policy violations


## </> Setting up Wazuh Lab
  - Import Wazuh OVA image
  - Onboard Ubuntu Server agent
  - Onboard Windows 11 machine agent



## 🧑‍💻Excercises
-  **Failed SSH Logins**: Detects repeated failed SSH login attempts within a short time frame, indicative of brute force attacks.  
-  **Unauthorized Access to Sensitive Files**: Alerts when unauthorized access is detected on files containing sensitive data or system configuration.  
-  **Executable File Modification**: Monitors changes to executable files and alerts on modifications, which could indicate malicious activity.  
-  **Anomalous Network Traffic**: Detects unusual patterns in network traffic such as large data transfers or unexpected protocols.  
-  **User Account Creation**: Notifies when a new user account is created on the system, which could be indicative of unauthorized access.  
-  **Abnormal Process Execution**: Alerts on the execution of uncommon or suspicious processes, potentially signaling malware activity.  
-  **Privilege Escalation Attempts**: Flags attempts to escalate user privileges, which may indicate an attempted compromise.
-  **Unusual Registry Modifications**: Monitors changes to the Windows registry and alerts on suspicious modifications, often associated with malware.
-  **Outbound Traffic to Known Malicious IPs**: Alerts when network traffic is observed to destinations with a history of malicious activity.
-  **Critical Service Stopped**: Notifies when critical system services are stopped unexpectedly, potentially indicating a disruption or compromise.
-  **Suspicious PowerShell Commands**: Alerts on the execution of suspicious PowerShell commands, often used by attackers for reconnaissance or exploitation.
-  **Unusual Account Activity**: Detects abnormal account activity such as multiple failed login attempts or login from unusual locations.
-  **Security Policy Violations**: Notifies when security policies, such as firewall rules or access controls, are violated, indicating potential security breaches.  


