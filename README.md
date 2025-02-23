# Active Directory

## Objective
This project involved setting up and securing an Active Directory environment on a Windows Server machine. The goal was to configure a domain, manage users, and test security mechanisms, including brute force detection and telemetry generation using Splunk and Atomic Red Team. The project was conducted in a virtualised environment using multiple virtual machines for both offensive and defensive testing.

### Skills Learned
Active Directory Configuration

    Installation and configuration of Active Directory Domain Services (AD DS).
    Promoting a Windows Server to a Domain Controller.
    Managing organisational units, users, groups, and group policies.
    Configuring DNS for proper domain resolution.

Security Monitoring and Telementry

    Implementing Sysmon and Splunk Universal Forwarder for log collection.
    Analysing security logs and event IDs for attack detection.
    Setting up alerts for suspicious activities in Splunk.

Offensive Security Techniques

    Using Kali Linux for a brute-force attack against domain accounts.
    Installing and using Crowbar for password attacks.
    Utilising the RockYou wordlist for credential cracking.


Defensive Measures and Detection

    Identifying brute force attempts via event ID 4625 in Splunk.
    Detecting successful logins and mapping attack sources via event ID 4624.
    Using MITRE ATT&CK techniques to simulate attacker behaviour.

Problem Solving and Adaptability

    Troubleshooting static IP address issues in Windows Server.
    Debugging Splunk access issues using the command-line interface.
    Managing high-resource utilisation in a virtualised environment.


### Tools Used
- Windows Server – Configured as an Active Directory Domain Controller.  
- Windows 10 – Target machine joined to the Active Directory domain.  
- Kali Linux – Used for penetration testing and brute-force attacks.  
- Splunk – Security Information and Event Management (SIEM) tool.  
- Sysmon – Monitors and logs system activity.  
- Atomic Red Team – Generates attack telemetry.  
- Crowbar – Brute-force attack tool.  
- MITRE ATT&CK Framework – Reference for attack techniques.  


## Steps

For a comprehensive and detailed overview of the course project, please refer to the following document:
[Active Directory](https://github.com/A7HXF/Active-Directory/blob/main/Active%20Directory%20Project.pdf)
