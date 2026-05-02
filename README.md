# University-IT-Projects
Laboratory projects and system administration scripts

# System Administration & Infrastructure Portfolio
A collection of technical projects and laboratory works focused on Linux/Windows administration, networking, and security. 

## 🛠 Tech Stack & Skills
* **Operating Systems:** Linux (Debian, RHEL, Ubuntu), Windows Server 2019.
* **Security & Auth:** PAM (Pluggable Authentication Modules), Faillock, Password Quality policies, SSH (Secure access/Key auth), Fail2Ban (WIP).
* **Storage & RAID:** mdadm (RAID 0, 1, 5, nested RAID), LVM, Ext4, Swap management.
* **Virtualization & Containers:** VMware, VirtualBox, **Docker (Basic container management)**.
* **Networking:** DHCP Failover, Routing, TCP/IP, **VPN (Basic setup)**.

## 🚀 Core Competencies

### 🛡 System Administration & Security
* **User & Group Management:** Creating and managing users/groups, implementing access control lists (ACL).
* **Permissions:** Advanced file system permissions management (`chmod`, `chown`, `sticky bit`).
* **Security Hardening (PAM):** Configuring modules in `/etc/pam.d/` to enforce system-wide security policies.
* **Account Lockout:** Implementing `pam_faillock` to prevent brute-force (configuring `deny`, `unlock_time`, and `even_deny_root`).
* **Password Complexity:** Enforcing strict requirements using `pam_pwquality` (minlen, dcredit, ucredit, etc.).
* **Remote Management:** Configuring and hardening SSH access for secure server administration.

### 💾 Storage & Disk Management (Linux)
* **Partitioning:** Professional use of `fdisk`, `gdisk`, and `blkid`.
* **Software RAID (mdadm):** * Implementing standard levels: RAID 0, 1, and 5.
    * Configuring **nested RAID** structures (e.g., RAID 1 over RAID 0 arrays) for high redundancy.
* **LVM (Logical Volume Management):** Full management of Physical Volumes (PV), Volume Groups (VG), and Logical Volumes (LV).
* **Mounting & Filesystems:** Initializing `ext4`, managing swap space, and configuring persistent storage via `/etc/fstab`.

### 🏢 Enterprise Infrastructure (Windows Server)
* **Active Directory:** AD DS installation, domain controller replication, and user management.
* **Network Services:** Configuring high-availability DHCP Failover.
* **File Services:** Implementing DFS (Distributed File System) for data redundancy.
* **Hybrid Integration:** Integrating Linux (Samba) into a Windows Domain environment.

---

## 📂 Project Files

### 🐧 Linux & Security Projects
* [**Security & Authentication Hardening**](5.pdf) — Setup of Debian security modules (PAM, Faillock, Password policies).
* [**Storage & LVM Management**](Montowanie%20zasobów%20lokalnychh.pdf) — Linux disk subsystem configuration and mounting/Building complex storage architectures (Nested RAID, LVM, Swap optimization).

### 🪟 Windows & Network Infrastructure
* [**Data Center Infrastructure Report**](sprawozdanie_Data_Center.pdf) — Detailed Windows Server & Hybrid AD setup.

---
*More projects, including an automated IPS (Intrusion Prevention System) with Fail2Ban, are coming soon.*
