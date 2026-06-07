# Cybersecurity Network Reconnaissance Lab

## Overview

This project demonstrates basic network reconnaissance techniques using Kali Linux and Metasploitable2 within a VirtualBox lab environment.

The objective was to understand how security professionals identify active hosts, discover open ports, enumerate services, and gather information about networked systems before conducting security assessments.

---

## Lab Environment

- Kali Linux
- Metasploitable2
- VirtualBox
- Nmap

---

## Network Configuration

| Machine | IP Address |
|----------|------------|
| Kali Linux | 192.168.56.109 |
| Metasploitable2 | 192.168.56.110 |

---

## Activities Performed

### 1. Connectivity Verification

Verified communication between systems using:

```bash
ping 192.168.56.110
```

### 2. Host Discovery

Performed host discovery using:

```bash
nmap -sn 192.168.56.110
```

### 3. Port Scanning

Identified open ports using:

```bash
nmap 192.168.56.110
```

### 4. Service Enumeration

Enumerated services and versions using:

```bash
nmap -sV 192.168.56.110
```

### 5. Operating System Detection

Performed OS fingerprinting using:

```bash
sudo nmap -O 192.168.56.110
```

---

## Skills Demonstrated

- Linux Administration
- Network Reconnaissance
- Host Discovery
- Port Scanning
- Service Enumeration
- Virtual Machine Networking
- Nmap Usage
- Cybersecurity Fundamentals

---

## Screenshots

### Host Discovery

![Host Discovery](screenshots/nmap the target.png)

### Port Scan

![Port Scan](screenshots/nmap the target.png)

### Service Enumeration

![Service Enumeration](screenshots/nmap-sV.png)

### OS Detection

![OS Detection](screenshots/sudo nmap the target.png)

---

## Learning Outcomes

- Understanding the reconnaissance phase of penetration testing.
- Identifying active hosts on a network.
- Enumerating exposed services.
- Using Nmap to gather system information.
- Building practical cybersecurity lab experience.