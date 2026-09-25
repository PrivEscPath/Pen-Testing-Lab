# Active Directory Penetration Testing Lab Architecture

## Overview

This lab provides an isolated Active Directory environment for practicing and documenting penetration testing techniques against Windows domain environments.

The environment is intentionally separated from production and general-purpose homelab systems so that vulnerable configurations, weak credentials, attack techniques, and security testing can be performed without affecting other systems.

## Objectives

The lab will be used to practice and document:

- Active Directory enumeration
- SMB and LDAP enumeration
- Kerberos attacks
- LLMNR/NBT-NS poisoning
- NTLM authentication attacks
- Password and credential attacks
- BloodHound attack-path analysis
- Credential dumping
- Lateral movement
- Privilege escalation
- Domain privilege escalation
- Post-exploitation
- Detection and remediation

## Lab Systems

| System | Operating System | Purpose |
|---|---|---|
| Domain Controller | Windows Server | Active Directory Domain Services and DNS |
| Windows Workstation | Windows 10/11 | Domain-joined attack target | X2
| Kali Linux | Kali Linux | Penetration testing / attacker system |

Additional Windows servers, workstations, users, services, and vulnerabilities will be added as the lab develops.

## Network Architecture

The penetration testing environment will reside on an isolated lab network.

Network segmentation and access controls will be configured to prevent the intentionally vulnerable systems from exposing services to untrusted networks or affecting other homelab systems.

A detailed network diagram will be added once I get time to build the diagram out.

## Security Notice

All systems within this environment are owned and controlled by me and are specifically configured for authorized security testing and educational purposes.
