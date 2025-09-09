# Active-Directory-Lab-1000-Users-w-PowerShell
Windows Server 2019 Active Directory lab with Windows 10 client, featuring domain setup, OU structure, and automated bulk user creation via PowerShell. 

## Lab Overview ##
- **Hypervisor:** Oracle VirtualBox
- **Server:** Windows Server 2019 (AD DS + DNS)
- **Client:** Windows 10 (domain joined)
- **Automation:** PowerShell script for 1000 users

## Project Structure

├── screenshots/         
├── scripts/
│   └── create-users.ps1
└── README.md

## Prerequisites

- Oracle VirtualBox (or any virtualization platform)  
- Windows Server 2019 ISO  
- Windows 10 ISO  
- Minimum 8 GB RAM and 60 GB free disk space  
- PowerShell (included in Server 2019 & Windows 10)

## Steps & Screenshots

### 1. VM Setup
![Step 1](screenshots/01.png)

### 2. Install Active Directory Domain Services (AD DS)
![Step 2](screenshots/02.png)

### 3. Promote Server to Domain Controller
![Step 3](screenshots/03.png)

### 4. Configure Organizational Units (OUs)
![Step 4](screenshots/04.png)

### 5. Join Windows 10 Client to Domain
![Step 5](screenshots/05.png)

### 6. Bulk User Creation with PowerShell
![Step 6](screenshots/06.png)

### 7. Verification
![Step 7](screenshots/07.png)
