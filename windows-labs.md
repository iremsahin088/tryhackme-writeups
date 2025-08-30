# Windows Labs Write-Ups

This file contains multiple Windows-focused TryHackMe lab write-ups to demonstrate practical cybersecurity skills.

---

## Lab 1: Windows Privilege Escalation

**Platform:** TryHackMe  
**Lab Type:** Windows Privilege Escalation  
**Objective:** Gain Administrator access on a Windows machine  

### Steps Taken
1. Enumerated users and group memberships:
```powershell
net user
net localgroup administrators
whoami
