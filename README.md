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
    ExploitDB: To find CVEs and to learn more about exploiting the machine
    Searchsploit: This is part of ExploitDB, CLI version.
    Github: We have dived into github to find these vulnerabilities and understand how they were used or coded.
    (Altough sometimes, vulnerabilities could be as simple as having a easy password as your VNC for example, which could lead me into your system.
    Nessus (optional): For vulnerability scanning and reporting.
    

Summary of Exploits

Various vulnerabilities, including weak authentication and deprecated protocols, were exploited to gain access to the system. Post-exploitation techniques were applied to maintain access and extract valuable information.
Lessons Learned

    Importance of strong authentication and proper service configurations.
    Risks associated with using outdated protocols and unpatched systems.
    Importance of understanding why we should isolate labs if deemed dangerous, it is best to set up your Metasploitable 2 lab as Host-Only, marked as the safest option and a good way to communicate with the metasploitable 2 Server.
