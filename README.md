## 🧩 Windows BIOS Troubleshooting Lab

This lab demonstrates real BIOS settings and troubleshooting use cases based on my previous technical experience.  
Each section documents an action I’ve used in real scenarios, such as enabling virtualization, adjusting boot order, or checking system logs.

---

### 1️⃣ BIOS Main Page Overview
This is the main page of the Dell G7 BIOS interface.  
It lists all available configuration categories such as System Information, Boot Sequence, Security, and Virtualization Support.  
I often started here when running system diagnostics or preparing a machine to boot from external media during installations.  

Don, my cat, reminds me from the very beginning that he has my hand — or maybe I have his — in case I need a quidance. 🐾

![BIOS Main Page](images/20251023_192147.jpg)
![BIOS Main Page with Don](images/20251023_192511.jpg)

---

### 2️⃣ Enabling Virtualization Support
This BIOS section shows where Intel Virtualization Technology can be enabled.  
Turning it on allows the CPU to support virtual machines and hardware acceleration — something I used when setting up Windows Server test environments and troubleshooting client-server connectivity during software installations.  

In practice, I worked with both **VirtualBox** and **VMware Workstation**, creating isolated virtual networks to simulate real deployment conditions.  
I installed the **server component of the software on a Windows Server virtual machine** and the **client component on a local machine**, verifying that the two could communicate properly through configured network ports.  
I tested these setups across **Windows Server 2012**, **Windows 10**, and **Ubuntu 18.04**, ensuring each environment could establish a stable connection once virtualization was enabled at the BIOS level.

![Virtualization Support](images/20251023_193056.jpg)
