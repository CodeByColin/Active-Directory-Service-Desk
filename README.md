# Active Directory Service Desk Lab

This project simulates a small enterprise Windows domain environment to demonstrate hands-on Tier 1 and Tier 2 IT Support skills. The lab was built in VirtualBox using Windows Server and focuses on Active Directory administration, user support, security policy enforcement, and role-based access control.

---

## Lab Environment

- **Domain Controller:** Windows Server 2022 (DC1)  
- **Domain:** lab.local  
- **Core Services:** Active Directory Domain Services (AD DS), DNS, Group Policy  
- **Departments:** HR, IT  
- **Security Groups:** HR, IT-Support  
- **File Services:** Departmental file shares with NTFS and share permissions  

---

## Skills & Tasks Demonstrated

### Tier 1 – Service Desk Operations
- User account creation and de-provisioning  
- Password resets and account unlocks  
- Group membership changes and access provisioning  
- Basic login and access troubleshooting  

### Tier 2 – Directory & Systems Administration
- Organizational Unit (OU) design and management  
- Group Policy creation and security baseline enforcement  
- Centralized password and authentication policy configuration  
- File share creation and least-privilege permission assignment  

---

## What Was Built

- A fully functional Windows domain (`lab.local`)
- Department-based OU structure (HR, IT, Employees, Workstations)
- Security groups for role-based access control
- Domain-level Group Policy enforcing password standards
- Shared file resources with access controlled by group membership

---

## Screenshot Walkthrough

| Screenshot | Description |
|-------------|-------------|
| <img width="1020" height="800" alt="Screenshot 2026-01-17 205049" src="https://github.com/user-attachments/assets/80a5073f-34ba-44c8-be3f-aecf6e8a095e" /> | Active Directory domain structure and OU layout |
| <img width="1019" height="767" alt="Screenshot 2026-01-17 161433" src="https://github.com/user-attachments/assets/ef1ab5b6-2b94-4794-8c7d-d393b399cee6" /> | User accounts created in Active Directory |
| <img width="1017" height="770" alt="Screenshot 2026-01-17 161542" src="https://github.com/user-attachments/assets/709d8f4f-f9b6-45e6-a209-2c5504c9ee79" /> | Security groups for HR and IT |
| <img width="1023" height="768" alt="Screenshot 2026-01-17 161640" src="https://github.com/user-attachments/assets/48f505a2-04d2-4957-b484-d55d8b55f790" /> | HR group membership and access assignment |
| <img width="1020" height="766" alt="Screenshot 2026-01-17 161721" src="https://github.com/user-attachments/assets/03983e6c-152a-45ae-ad68-e7d1cb3701cf" /> | IT-Support group membership |
| <img width="1018" height="765" alt="Screenshot 2026-01-17 161916" src="https://github.com/user-attachments/assets/ca829d24-cce3-4903-9296-eca6a72c9011" /> | Password reset and account unlock operation |
| <img width="1019" height="767" alt="Screenshot 2026-01-17 161947" src="https://github.com/user-attachments/assets/7706f7df-e961-45b0-be75-c1604b6dd3e8" /> | User disable and re-enable (account lifecycle) |
| <img width="1017" height="765" alt="Screenshot 2026-01-17 161957" src="https://github.com/user-attachments/assets/6e9c8938-629f-491a-840a-0f0c117e31a5" /> | Departmental OU structure |
| <img width="1020" height="765" alt="Screenshot 2026-01-17 162522" src="https://github.com/user-attachments/assets/dfda920a-7699-4da0-b8a5-2becc4eafd72" />` | Group Policy enforcing password security baseline |
| <img width="1021" height="765" alt="Screenshot 2026-01-17 163521" src="https://github.com/user-attachments/assets/a5b7a4c0-a324-4810-b795-7cc34f2c4a9d" /> | NTFS and share permissions for departmental file access |

---
