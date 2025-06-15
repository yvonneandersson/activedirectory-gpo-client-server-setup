# Windows Client-Server Configuration with AD, GPO, and File Sharing

This project simulates the deployment of a Windows-based IT infrastructure for a small organization using **Windows Server 2019** and **Windows 10 Education**. It includes domain configuration, user and group management, file sharing with correct permissions, and policy enforcement via Group Policy.

---

## 🧱 Project Scope

- ✅ Domain setup with **Active Directory Domain Services (AD DS)**
- ✅ DNS Server configuration with forwarding
- ✅ Group Policy Objects for:
  - Folder redirection
  - Password rules
  - CTRL+ALT+DEL login requirement
- ✅ User templates with automated group assignment
- ✅ File server with:
  - Home directories (`Hem_kataloger`)
  - Group shares (`Gruppkataloger`)
- ✅ Correct NTFS permissions for each share and role
- ✅ Dual domain controllers (DC01, DC02)
- ✅ Static IP configurations, IPv6 disabled
- ✅ Remote Server Administration Tools (RSAT) for management
- ✅ Error handling and fixes documented in a [Change Log](./documents/Change_Log.pdf)

---

## 🧪 Clients

- **KlientAdmin**: Administrative client for domain management
- **Klient01**: Standard user workstation
- **Both clients** are joined to the domain `Grupp60.lab`

---

## 🔧 Servers

- **DC01**: Primary domain controller with Desktop Experience
- **DC02**: Secondary controller using Windows Server Core
- **Both servers** include AD and DNS roles

---

## 📄 Change Log

All steps, changes, fixes, and configurations have been carefully documented in this PDF:

📄 [View Full Change Log (PDF)](./documents/Change_Log.pdf)

---

