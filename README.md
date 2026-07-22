# Linux Fundamentals & System Administration Lab

> Hands-on Linux system administration exercises completed in a Kali Linux virtual machine as part of my cybersecurity training.

## Project Overview

This repository demonstrates practical Linux administration skills that are essential for cybersecurity professionals. The lab covers file management, Linux permissions, software administration, networking, and Bash scripting through real-world command-line exercises performed on Kali Linux. :contentReference[oaicite:0]{index=0}

Rather than focusing on theory, this project emphasizes practical skills used by SOC Analysts, System Administrators, Penetration Testers, and Blue Team professionals.

---

## Objectives

The goal of this project was to gain hands-on experience with core Linux administration tasks including:

- File and directory management
- Linux file permissions
- User and system information gathering
- Software package management
- Network troubleshooting
- Bash scripting and automation

These are foundational skills required in cybersecurity operations. :contentReference[oaicite:1]{index=1}

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Operating System | Kali Linux |
| Virtualization | Oracle VirtualBox |
| Shell | Bash |
| Package Manager | APT |
| Networking Tools | ip, route, ping, nslookup |
| Permission Management | chmod |
| System Information | whoami, hostname, uname |

---

# Skills Demonstrated

## 1. File & Directory Management

Created and navigated directories using the Linux command line.

### Commands Used

```bash
mkdir
cd
pwd
touch
ls
ls -l
```

### Tasks Performed

- Created working directories
- Navigated the filesystem
- Created multiple files
- Verified file creation
- Listed directory contents

### Cybersecurity Relevance

Understanding the Linux filesystem is fundamental for:

- Digital Forensics
- Log Analysis
- Malware Investigation
- Incident Response
- Secure File Management

---

## 2. Linux File Permissions

Modified file permissions using `chmod`.

### Commands Used

```bash
chmod
ls -l
```

### Tasks Performed

- Removed write permissions
- Restored permissions
- Assigned execute permissions
- Verified permission changes

### Cybersecurity Relevance

Linux permissions implement the **Principle of Least Privilege**, helping reduce unauthorized access to files and systems. :contentReference[oaicite:2]{index=2}

---

## 3. Basic System Administration

Collected important operating system information.

### Commands Used

```bash
whoami
hostname
uname
uname -a
date
```

### Skills Gained

- Identify current user
- View kernel version
- Gather system information
- Verify host identity

### Cybersecurity Relevance

System reconnaissance is often the first step in:

- Security Assessments
- Vulnerability Management
- Incident Response
- Asset Inventory

:contentReference[oaicite:3]{index=3}

---

## 4. Software Management

Managed software packages using APT.

### Commands Used

```bash
sudo apt update
sudo apt remove
```

### Tasks Performed

- Updated package repositories
- Removed installed packages
- Verified package management

### Cybersecurity Relevance

Keeping systems updated reduces exposure to known vulnerabilities and is a critical security best practice. :contentReference[oaicite:4]{index=4}

---

## 5. Network Connectivity

Verified network configuration and connectivity.

### Commands Used

```bash
ip addr
route
ping
nslookup
```

### Tasks Performed

- Examined network interfaces
- Verified routing table
- Tested Internet connectivity
- Performed DNS lookups

### Cybersecurity Relevance

Network troubleshooting skills are essential for:

- SOC Monitoring
- Threat Hunting
- Firewall Troubleshooting
- Network Security Analysis

:contentReference[oaicite:5]{index=5}

---

## 6. Shell Scripting & Automation

Created and executed a Bash script.

### Commands Used

```bash
nano
chmod +x
./backup.sh
```

### Tasks Performed

- Created a Bash script
- Assigned executable permissions
- Executed the script successfully

### Cybersecurity Relevance

Automation is widely used in cybersecurity for:

- Log Collection
- System Monitoring
- Backups
- Security Auditing
- Repetitive Administrative Tasks

:contentReference[oaicite:6]{index=6}

---

# Project Structure

```
Linux-Fundamentals/
│
├── README.md
├── report.pdf
├── screenshots/
│   ├── file-management/
│   ├── permissions/
│   ├── system-admin/
│   ├── software-management/
│   ├── networking/
│   └── shell-scripting/
│
└── scripts/
    └── backup.sh
```

---

# Key Linux Commands Practiced

### File Management

```bash
mkdir
cd
pwd
touch
ls
```

### Permissions

```bash
chmod
ls -l
```

### System Information

```bash
whoami
hostname
uname
date
```

### Package Management

```bash
apt update
apt remove
```

### Networking

```bash
ip addr
route
ping
nslookup
```

### Shell Scripting

```bash
nano
chmod +x
./backup.sh
```

---

# Screenshots

The project includes screenshots demonstrating the successful completion of every task performed in the Kali Linux virtual machine. :contentReference[oaicite:7]{index=7}

Examples include:

- File creation
- Directory navigation
- Permission changes
- System information
- Package updates
- Network connectivity
- Bash script execution

---

# Key Cybersecurity Concepts Reinforced

- Linux Administration
- Principle of Least Privilege
- System Hardening
- Network Troubleshooting
- Bash Automation
- Command Line Proficiency
- File Security
- System Enumeration

---

# What I Learned

Through this project, I developed practical experience in Linux system administration that forms the foundation for cybersecurity roles such as:

- SOC Analyst
- Cybersecurity Analyst
- Linux Administrator
- Security Engineer
- Incident Responder
- Penetration Tester

The exercises strengthened my confidence using the Linux command line while demonstrating how administration skills directly support defensive security operations. :contentReference[oaicite:8]{index=8}

---

# Future Improvements

- User and Group Management
- Cron Job Automation
- Log Analysis
- Firewall Configuration
- SSH Hardening
- Bash Script Enhancements
- System Monitoring
- Linux Security Auditing

---

## Author

**Raheemah Lartey**

Cybersecurity Analyst (Transitioning) | SOC Enthusiast | Linux | Networking | SIEM | Python

📧 LinkedIn: *www.linkedin.com/in/raheemah-lartey*

🌐 GitHub: *https://github.com/rah102993/Linux-command-line-basics*

---

> *This project is part of my cybersecurity learning journey and demonstrates practical Linux administration skills commonly used in Security Operations Centers (SOC), system administration, and incident response.*
