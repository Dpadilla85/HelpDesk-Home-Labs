# Help Desk Simulation Project

## Overview
This project is a hands-on IT support and systems administration home lab built to simulate a real-world help desk environment. The lab was created using VirtualBox and includes Windows 11, Ubuntu Linux, and Windows Server 2022 systems.

The goal of this project was to practice core IT support, Active Directory administration, troubleshooting, remote access, networking, and security fundamentals in a controlled environment.

---

## 🏗️ Architecture Overview

This lab simulates a small enterprise IT environment using virtual machines connected through an internal virtual network.


### Components

#### Host Machine
- Runs VirtualBox to host and manage all virtual machines

#### Windows Server 2022 (DC01)
- Domain Controller
- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management

#### Windows 11 Client (WIN11-CLIENT)
- Domain-joined workstation
- Simulates end-user environment
- Used for troubleshooting and ticket resolution

#### Ubuntu Linux (UBUNTU01)
- Administrative and testing system
- Remote access via SSH and VNC
- Can host or interact with the ticketing system

#### Peppermint Ticketing System
- Simulates help desk workflows
- Used to create, track, and resolve support tickets

### Network Configuration
- VirtualBox Internal Network used to simulate a LAN environment
- All machines assigned private IP addresses
- Domain Controller provides DNS services
- Clients communicate with DC for authentication and policy enforcement

### Authentication Flow
1. User logs into Windows 11 client
2. Credentials are sent to the Domain Controller
3. Active Directory authenticates the user
4. Group Policy Objects (GPOs) are applied
5. Access is granted based on permissions

---

## 🧪 Lab Environment
- Virtualization: VirtualBox
- Operating Systems:
  - Windows 11
  - Ubuntu Linux
  - Windows Server 2022
- Tools & Services:
  - Active Directory Domain Services (AD DS)
  - Group Policy Management
  - Peppermint Ticketing System
  - Remote Desktop Protocol (RDP)
  - SSH
  - VNC

---

## 🎯 Project Objectives
- Build a virtualized IT lab environment
- Configure and manage an Active Directory domain
- Simulate help desk workflows using a ticketing system
- Troubleshoot real-world IT issues across multiple systems
- Practice user administration and permissions management
- Apply networking and security concepts

---

## 🔧 Key Tasks Completed
- Built a virtualized IT environment using VirtualBox
- Configured an Active Directory domain
- Created and managed users and groups
- Applied Group Policy Objects (GPOs)
- Installed and configured Peppermint ticketing system
- Resolved simulated help desk tickets:
  - Account lockouts
  - Permissions issues
  - Software installations
- Performed system administration tasks:
  - User management
  - File permissions
  - System updates
- Used remote support tools:
  - RDP
  - SSH
  - VNC
- Diagnosed networking issues using:
  - ping
  - ipconfig
  - netstat
- Applied security concepts:
  - MFA
  - IAM
  - Phishing awareness

---

## 🧠 Skills Demonstrated
- Active Directory Administration
- Help Desk Support
- Windows Server Management
- Group Policy Configuration
- Ticketing System Workflow
- Remote Troubleshooting
- Network Diagnostics
- Linux & Windows Administration
- Identity & Access Management (IAM)
- Security Best Practices

---

## 🛠️ Example Troubleshooting Scenarios

### Account Lockout
- Identified locked account in Active Directory
- Unlocked account and reset credentials
- Verified successful login

### File Permission Issue
- Diagnosed access denial
- Reviewed NTFS and share permissions
- Updated group membership

### Software Installation
- Used admin privileges to install software remotely
- Verified application functionality

### Network Connectivity
- Diagnosed issue using ping, ipconfig, and netstat
- Restored connectivity between systems

---

## 🔐 Security Concepts Practiced
- Multi-Factor Authentication (MFA)
- Identity and Access Management (IAM)
- Principle of Least Privilege
- Access Control Enforcement
- Phishing Awareness

---

## 📸 Screenshots
Add screenshots in a /screenshots folder such as:
- Active Directory Users & Computers
- Group Policy Management
- Peppermint Dashboard
- Remote Desktop Session
- Command-line troubleshooting

---

## 📚 What I Learned
This project strengthened my ability to troubleshoot IT issues, manage Active Directory environments, work across Windows and Linux systems, use remote administration tools, and apply security best practices in realistic scenarios.

---

## 🚀 Future Improvements
- Automate tasks with PowerShell
- Add shared drives and printer services
- Expand Group Policy configurations
- Integrate SIEM/log monitoring tools
- Simulate advanced enterprise scenarios
- Implement backup and recovery systems

---

## 👤 Author
Your Name

---

## 📄 License
This project is licensed under the MIT License.
