Metasploitable 2 Penetration Testing
Overview

This project involves penetration testing of the Metasploitable 2 virtual machine, a deliberately vulnerable system designed for practicing security testing techniques. The goal of this exercise is to identify and exploit known vulnerabilities to simulate real-world attack scenarios.
Objectives

    Scan the target machine to discover open ports and services.
    Identify vulnerabilities and execute exploits using various penetration testing tools.
    Document the process, including scanning, exploitation, and post-exploitation activities.

Environment

    Attacker Machine: Kali Linux
    Target Machine: Metasploitable 2
    Network Setup: Host-Only Adapter for secure communication between the VMs.

Tools Used

    Nmap: For network scanning and service enumeration.
    Metasploit: To exploit vulnerabilities on the target machine.
    Nessus (optional): For vulnerability scanning and reporting.

Summary of Exploits

Various vulnerabilities, including weak authentication and deprecated protocols, were exploited to gain access to the system. Post-exploitation techniques were applied to maintain access and extract valuable information.
Lessons Learned

    Importance of strong authentication and proper service configurations.
    Risks associated with using outdated protocols and unpatched systems.
