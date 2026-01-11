# Secure Linux Server Hardening

## 📌 Project Overview
This is my first cybersecurity project.  
The goal is to harden an Ubuntu server by applying basic Linux security best practices.

## 🎯 Objectives
- Reduce attack surface
- Secure SSH access
- Protect against brute-force attacks
- Apply basic firewall rules

## 🖥️ Environment
- OS: Ubuntu Server 20.04
- Access: SSH
- User: Non-root sudo user

## 🛠️ Tools Used
- OpenSSH
- UFW
- Fail2Ban

## 🔐 Security Measures Implemented
- Disabled root SSH login
- Enforced SSH key-based authentication
- Changed default SSH port
- Configured firewall with UFW
- Enabled brute-force protection with Fail2Ban

## 📊 Results
- SSH brute-force attempts blocked
- Only authorized access allowed
- Reduced exposure to common attacks

## 📚 What I Learned
- Linux user and access management
- SSH security fundamentals
- Firewall configuration basics
- Importance of defense in depth

## 🚀 Next Improvements
- Add system auditing (Auditd)
- Add file integrity monitoring
- Automate hardening with Bash script
