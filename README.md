# Learn-SecByte-CTF-Labs-Collection-OSINT-Nmap-Scanning-Wireshark-Cryptography-Fundamentals
A curated collection of hands-on cybersecurity CTF labs covering OSINT Footprinting, Nmap Network Scanning, Service Enumeration Mastery, Wireshark Packet Analysis, Cryptography Foundations, Web Technologies, and Home Lab Setup from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on Open Source Intelligence (OSINT) footprinting, network scanning with Nmap, service enumeration mastery, Wireshark packet capture analysis, cryptography fundamentals, OS file systems and terminal mechanics, and secure lab building exercises designed for cybersecurity students, CTF players, security analysts, network engineers, and entry-level penetration testers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Building a successful career in cybersecurity requires a rock-solid foundation across terminal navigation, operating system internals, network traffic analysis, and structured intelligence gathering. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational collection of CTF challenge labs provides essential hands-on training for mastering core technical concepts.

From building a dedicated, secure home lab environment and mastering command-line interfaces (Linux Terminal & Windows command-line) to executing OSINT footprinting, running advanced Nmap service enumeration, sniffing packet streams in Wireshark, understanding symmetric/asymmetric cryptography, and auditing web protocol primitives, these labs lay the foundation for all technical security disciplines.

---

## Lab Collection & Index

Below is the complete, searchable index of all OSINT, network scanning, packet analysis, OS foundations, cryptography, and lab architecture challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Packet Analysis with Wireshark** | Network Inspection & Enumeration | TCP stream reconstruction, PCAP display filters, protocol breakdown (HTTP/DNS/TLS), anomaly detection | [Access Lab](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark) |
| 2 | **Service Enumeration Mastery** | Network Inspection & Enumeration | Version detection, banner grabbing, service-specific probing (SMB, SSH, FTP, HTTP, SNMP), NSE scripting | [Access Lab](https://learn.secbyte.org/ctf/service-enumeration-mastery) |
| 3 | **Network Scanning with Nmap** | Network Inspection & Enumeration | Host discovery, SYN/Connect/UDP scans, timing parameters (`-T0` to `-T5`), port state interpretation | [Access Lab](https://learn.secbyte.org/ctf/network-scanning-with-nmap-4) |
| 4 | **Information Gathering and Reconnaissance Mastery** | OSINT & Reconnaissance | Passive/active recon methodologies, target profiling, public footprinting, metadata extraction | [Access Lab](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance-mastery) |
| 5 | **Open Source Intelligence: Footprints & Threat Context** | OSINT & Reconnaissance | Threat actor intelligence context, social media OSINT, WHOIS/DNS history, breach data correlation | [Access Lab](https://learn.secbyte.org/ctf/open-source-intelligence-footprints-threat-context) |
| 6 | **Building a Secure Home Lab** | OS & Environment Setup | Hypervisor setup (VirtualBox/VMware), isolated network bridging, pfSense firewall rules, target VM deployment | [Access Lab](https://learn.secbyte.org/ctf/building-a-secure-home-lab) |
| 7 | **Web Technologies for Security Foundations** | Web & Cryptography Fundamentals | HTTP request/response model, headers, cookies, WebSockets, DOM mechanics, web security basics | [Access Lab](https://learn.secbyte.org/ctf/web-technologies-for-security-foundations) |
| 8 | **Authentication & Access Control Interactive Room** | Web & Cryptography Fundamentals | Session management, RBAC vs. ABAC models, multi-factor authentication (MFA) mechanisms, IDOR basics | [Access Lab](https://learn.secbyte.org/ctf/authentication-access-control-interactive-room) |
| 9 | **Introduction to Cryptography** | Web & Cryptography Fundamentals | Symmetric/Asymmetric encryption (AES, RSA), cryptographic hashing (SHA256), digital signatures, PKI | [Access Lab](https://learn.secbyte.org/ctf/introduction-to-cryptography) |
| 10 | **File Fundamentals: Processes, Permissions & Filesystems** | OS & Environment Setup | File descriptors, Linux/Windows permission structures (chmod/ACLs), process creation, inode mechanics | [Access Lab](https://learn.secbyte.org/ctf/file-fundamentals-processes-permissions-filesystems) |
| 11 | **Terminal Foundations** | OS & Environment Setup | Bash/CLI navigation, command piping, environment variables, I/O redirection (`>`,`>>`,`<`), scripting basics | [Access Lab](https://learn.secbyte.org/ctf/terminal-foundations) |
| 12 | **Windows for Cybersecurity** | OS & Environment Setup | Windows architecture, Registry hives, PowerShell cmdlets, Event Viewer auditing, User Account Control (UAC) | [Access Lab](https://learn.secbyte.org/ctf/windows-for-cybersecurity) |

---

## Categories

### 1. OS Foundations, Terminal & Home Lab Setup
Master command-line productivity, understand operating system internals across Linux and Windows, and build an isolated security testing environment.
- [Building a Secure Home Lab](https://learn.secbyte.org/ctf/building-a-secure-home-lab)
- [Terminal Foundations](https://learn.secbyte.org/ctf/terminal-foundations)
- [File Fundamentals: Processes, Permissions & Filesystems](https://learn.secbyte.org/ctf/file-fundamentals-processes-permissions-filesystems)
- [Windows for Cybersecurity](https://learn.secbyte.org/ctf/windows-for-cybersecurity)

### 2. OSINT, Reconnaissance & Threat Footprinting
Gather external threat intelligence, profile organizations, and map attack surface footprints without generating aggressive network noise.
- [Information Gathering and Reconnaissance Mastery](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance-mastery)
- [Open Source Intelligence: Footprints & Threat Context](https://learn.secbyte.org/ctf/open-source-intelligence-footprints-threat-context)

### 3. Network Scanning, Service Enumeration & Packet Inspection
Scan active targets, identify running network services, grab service banners, and analyze PCAP packet captures in Wireshark.
- [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-4)
- [Service Enumeration Mastery](https://learn.secbyte.org/ctf/service-enumeration-mastery)
- [Packet Analysis with Wireshark](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark)

### 4. Web Security, Cryptography & Access Control
Understand core web protocols, cryptographic ciphers, hashing algorithms, and identity access control models.
- [Web Technologies for Security Foundations](https://learn.secbyte.org/ctf/web-technologies-for-security-foundations)
- [Authentication & Access Control Interactive Room](https://learn.secbyte.org/ctf/authentication-access-control-interactive-room)
- [Introduction to Cryptography](https://learn.secbyte.org/ctf/introduction-to-cryptography)

---

## Learning Path

Follow this structured progression path to build foundational operational readiness across security engineering, network defense, and ethical hacking:

1. **Phase 1: Lab Architecture, OS Foundations & Terminal Mastery** — Setup a secure research environment and master command-line operations:
   - [Building a Secure Home Lab](https://learn.secbyte.org/ctf/building-a-secure-home-lab)
   - [Terminal Foundations](https://learn.secbyte.org/ctf/terminal-foundations)
   - [File Fundamentals: Processes, Permissions & Filesystems](https://learn.secbyte.org/ctf/file-fundamentals-processes-permissions-filesystems)
   - [Windows for Cybersecurity](https://learn.secbyte.org/ctf/windows-for-cybersecurity)

2. **Phase 2: OSINT, Intelligence Gathering & Network Scanning** — Profile target footprints and enumerate active network services:
   - [Information Gathering and Reconnaissance Mastery](https://learn.secbyte.org/ctf/information-gathering-and-reconnaissance-mastery)
   - [Open Source Intelligence: Footprints & Threat Context](https://learn.secbyte.org/ctf/open-source-intelligence-footprints-threat-context)
   - [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap-4)
   - [Service Enumeration Mastery](https://learn.secbyte.org/ctf/service-enumeration-mastery)

3. **Phase 3: Packet Inspection & Network Forensics** — Analyze raw network traffic captures to detect security anomalies:
   - [Packet Analysis with Wireshark](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark)

4. **Phase 4: Web Protocols, Cryptography & Access Control** — Master web application fundamentals, encryption, and authentication:
   - [Web Technologies for Security Foundations](https://learn.secbyte.org/ctf/web-technologies-for-security-foundations)
   - [Authentication & Access Control Interactive Room](https://learn.secbyte.org/ctf/authentication-access-control-interactive-room)
   - [Introduction to Cryptography](https://learn.secbyte.org/ctf/introduction-to-cryptography)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and target specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy security tools (Nmap, Wireshark, OpenSSL, Maltego, CyberChef, VirtualBox/VMware) inside your security laboratory.
4. Execute terminal commands, perform OSINT queries, run Nmap scans, parse packet streams, solve cryptographic ciphers, and retrieve target flags.

---

## Disclaimer

This repository and its linked resources are strictly designed for educational, threat research, and authorized technical security training purposes. Never execute network port scans, OSINT investigations on private individuals, or packet sniffing utilities against unauthorized systems, production infrastructure, or third-party networks.
