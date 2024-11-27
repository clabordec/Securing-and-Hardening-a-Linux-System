# Securing and Hardening a Linux System

## Table of Contents
- About the Project
- Features
- Tools and Techniques
- Usage
- Contributing
- License
- Contact

<br>

## About the Project
Securing and Hardening a Linux System is a comprehensive guide and toolkit for Linux system administrators to secure Linux servers and systems effectively. This project provides step-by-step methods, tools, and scripts to minimize vulnerabilities, enforce security policies, and meet compliance standards.

<br>

## Features
- Automated security hardening scripts
- Guides for configuring firewalls, SELinux, and AppArmor
- Logging and monitoring solutions
- Tools for scanning and auditing system vulnerabilities
- Secure user and group management
- Advanced encryption and secure communications setup
- Guides for securing web servers (Apache, NGINX) and database servers

<br>

## Tools and Techniques
The project leverages the following tools and techniques:
- Firewalls: iptables, ufw, and firewalld
- Access Controls: SELinux, AppArmor, and PAM (Pluggable Authentication Modules)
- Auditing Tools:
  - Lynis: Comprehensive security auditing tool
  - chkrootkit and rkhunter: Rootkit detection tools
- Encryption:
  - OpenSSL for file and communication encryption
  - GPG for secure file transfer
- Monitoring and Logging:
  - syslog, auditd, and custom logging configurations
  - Tools like fail2ban and logwatch for intrusion detection
- Package and Patch Management: `unattended-upgrades`, `yum-cron`, and manual patching guides
- Secure SSH:
  - Key-based authentication
  - Disabling root login and enforcing strong ciphers
- User Management:
  - Enforcing strong passwords with pwquality
  - Removing inactive users and unused groups
- Web and Database Security:
  - Best practices for Apache, NGINX, and MySQL
  - Configurations to prevent SQL injections and XSS attacks

<br>

## Usage
- Execute scripts based on specific tasks:
  - Firewall setup: ./configure_firewall.sh
  - User and group auditing: ./audit_users.sh
- Check system health and vulnerabilities:
```bash
./scan_vulnerabilities.sh
```
Customize configurations to suit your needs. The configuration files are located in the configs/ directory.

<br>

## Contact
Project Maintainer: Chaanyah Laborde
Email: chaanyahlaborde@gmail.com
GitHub: Cahn20
