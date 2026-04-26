# 🖥️ Windows Server 2019 — Active Directory Home Lab

## 📋 Project Overview
Built a complete Active Directory home lab using VirtualBox 
to simulate a real enterprise IT environment.

## 🛠️ Tools & Technologies
| Tool | Version |
|------|---------|
| Windows Server | 2019 |
| Windows Client | 10 Pro |
| Virtualization | Oracle VirtualBox |
| Network Type | Host-Only Adapter |

## ✅ What I Built
| Task | Status |
|------|--------|
| Domain Controller Setup | ✅ Done |
| DNS Configuration | ✅ Done |
| Domain Join (Windows 10) | ✅ Done |
| User Creation (ali, Khan) | ✅ Done |
| Security Group (IT-Team) | ✅ Done |
| Group Policy — Wallpaper | ✅ Done |
| Group Policy — Network Drive | ✅ Done |
| Shared Folder Permissions | ✅ Done |

---

## 📸 Screenshots

### 🖥️ Server Side

*1️⃣ Server IP Configuration*


![Server IP](Server-IP-Configuration.png)


> Configured static IP 192.168.56.10 on Domain Controller 
> using Host-Only adapter in VirtualBox

---

*2️⃣ Active Directory Users*


![AD Users](Active-Directory%20Users.png)


> Created domain users ali and Khan in Active Directory 
> Users and Computers under itlab.local domain

---

*3️⃣ AD User List*


![AD User List](AD%20User%20List.png)


> Full list of Active Directory users showing ali and Khan 
> both enabled and active in itlab.local domain

---

*4️⃣ IT-Team Security Group Members*


![IT-Team](IT-Team%20Goup%20Mambers.png)


> Created Security Group IT-Team and added ali and Khan 
> as members for centralized permission management

---

*5️⃣ DNS Zone Configuration*


![DNS Zone](DNS%20ZONE.png)


> Configured DNS Forward Lookup Zone for itlab.local with 
> all required SRV, A, NS and SOA records for AD to work

---

*6️⃣ Group Policy Objects*


![GPO](Group%20Policy%20Objects.png)


> Created two GPOs linked to itlab.local:
> Desktop-Policy (wallpaper) and Network-Drive-Policy (Z: drive)

---

*7️⃣ Shared Folder*


![Shared Folder](Shared%20Folder.png)


> Created ITLabShare with Full Control permissions 
> assigned to IT-Team security group

---

*8️⃣ Domain Controller Proof*


![DC Proof](Domain%20Controller%20Proof.png)


> Verified Domain Controller role, domain name itlab.local 
> and all Active Directory services running correctly

---

### 💻 Windows 10 Client Side

*9️⃣ Domain Login Proof*


![Domain Login](Domain%20Login%20Proof.png)


> Successfully logged into Windows 10 using domain 
> credentials itlab\Khan proving successful domain join

---

*🔟 Z: Drive Auto Mapped*


![Z Drive](Z%20Drive%20Mapped.png)


> Network drive Z: automatically mapped on login via 
> Group Policy for all domain users without manual setup

---

*1️⃣1️⃣ Shared Files Access*


![Shared Files](Shared%20Files.png)


> Both users ali and Khan successfully created, read 
> and deleted files proving Full Control permissions working

---

*1️⃣2️⃣ GPO Wallpaper Applied*


![GPO Wallpaper](GPO%20Wallpaper%20Applied.png)


> Desktop wallpaper automatically enforced on Windows 10 
> client via Group Policy proving GPO applied successfully

---

*1️⃣3️⃣ Network Settings*


![Network](Network%20Setting.png)


> Windows 10 client DNS configured pointing to Domain 
> Controller 192.168.56.10 enabling AD communication

---

## 🎯 Skills Demonstrated
- Active Directory Administration
- DNS Configuration & Troubleshooting
- Group Policy Object (GPO) Management
- Network File Sharing & NTFS Permissions
- VirtualBox Network Configuration
- Windows Server 2019 Administration
- Domain User & Group Management
- Static IP & Network Troubleshooting
