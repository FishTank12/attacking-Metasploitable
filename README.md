# Metasploitable 2 Penetration Testing

## Table of Contents
- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Scanning](#scanning)
- [Exploitation](#exploitation)
- [Post-Exploitation](#post-exploitation)
- [Lessons Learned](#lessons-learned)
- [References](#references)

## Introduction
This repository documents the process of attacking the Metasploitable 2 virtual machine using various penetration testing techniques. The goal was to identify and exploit vulnerabilities to gain access to the system, simulating real-world attack scenarios.

## Environment Setup
- **Attacker VM:**
  - Operating System: [Your Attacker OS] (e.g., Kali Linux, Ubuntu)
  - IP Address: 192.168.56.10

- **Target VM:**
  - Operating System: Metasploitable 2
  - IP Address: 192.168.56.11

### Network Configuration
- Both VMs were configured to use a **Host-Only Adapter** to allow communication between them.

## Scanning
1. **Initial Reconnaissance:**
   - Used the `ping` command to confirm connectivity.
   ```bash
   ping 192.168.56.11
