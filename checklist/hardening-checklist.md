# Linux Server Hardening Checklist

## User & Access
- [x] Created non-root sudo user
- [x] Disabled root SSH login
- [x] SSH key authentication enabled

## SSH Hardening
- [x] Changed default SSH port
- [x] Disabled password authentication
- [x] Disabled empty passwords

## Firewall (UFW)
- [x] Default deny incoming traffic
- [x] Allowed SSH port only
- [x] Enabled UFW logging

## Brute-Force Protection
- [x] Installed Fail2Ban
- [x] Enabled SSH jail
- [x] Verified IP banning

