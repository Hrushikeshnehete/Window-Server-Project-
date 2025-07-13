# Window-Server-Project-

 Project Overview  
This project involves setting up and configuring a Windows Server environment to provide essential network services, including Active Directory, Group Policy, file sharing, print services, FTP, web hosting, DHCP, and backup solutions. The goal is to create a secure, efficient, and scalable IT infrastructure.  

---

 Installation & Configuration Steps 

 1. Active Directory Setup 
- Installed **Active Directory Domain Services (AD DS).  
- Created users (`hruser1`, `salesuser1`, `ituser1`) and groups for role-based access control.  

 2. Group Policy Configuration  
- Configured Group Policy Objects (GPOs) to enforce security policies and system settings.  
- Created a "Security Policy" group to manage permissions centrally.  

 3. File Sharing & Permissions  
- Created a shared folder and assigned read/write permissions to specific users.  

 4. Print Server Setup  
- Added a virtual printer and granted SalesUsers print permissions.  
- Tested printing from a client machine.  

5. Firewall & Remote Access  
- Configured firewall rules to allow HTTP (TCP 80) and FTP (TCP 21).  
- Enabled Remote Desktop (RDP) for secure remote administration.  

6. FTP Server Deployment 
- Installed FTP services via IIS.  
- Created an FTP site at `C:\FTPRoot` with basic authentication.  
- Added a user (`ftpuser`) with read/write access and tested file transfers using FileZilla.  

7. Web Hosting (IIS)
- Installed Internet Information Services (IIS).  
- Hosted a website on port 80 and generated a self-signed certificate.  

8. DHCP Server Configuration  
- Installed the DHCP role and defined an IP address scope(`192.168.1.100-192.168.1.200`).  
- Authorized the DHCP server for automatic client IP assignments.  

9. Backup & Recovery  
- Installed Windows Server Backup** and scheduled daily backups of `C:\sharedDocs`.  
- Tested file restoration to ensure data recovery.  

---

 Technical Requirements  
- OS: Windows Server 2022  
- Tools Used:  
  - Server Manager  
  - Group Policy Management  
  - IIS Manager  
  - DHCP Console  
  - Windows PowerShell (for firewall rules)  

---

#WindowsServer #ActiveDirectory #SysAdmin #ITInfrastructure #NetworkSecurity 

---  
