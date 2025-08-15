# Villain Framework Reverse Shell Report

## ⚙️ Setup Info
- **Payload:** `windows/reverse_tcp/powershell`
- **LHOST:** 192.168.56.101
- **LPORT:** 4444

## 🔁 Payload Delivery Method
The payload was generated using Villain’s payload creation module with the specified LHOST and LPORT values.  
It was transferred to the target Windows VM via a shared folder.  
On the target VM, the PowerShell payload was executed manually, establishing a reverse shell connection to the attacker machine running Villain.

## 🖥️ Captured Info
- **Hostname:** WIN-7LAB-PC
- **IP Address:** 192.168.56.102
- **User:** win7lab\student

## 🔎 Enumeration Performed
```powershell
whoami
win7lab\student

ipconfig
IPv4 Address. . . . . . . . . . . : 192.168.56.102
Subnet Mask . . . . . . . . . . . : 255.255.255.0
Default Gateway . . . . . . . . . : 192.168.56.1

systeminfo
OS Name: Microsoft Windows 7 Professional
OS Version: 6.1.7601 Service Pack 1 Build 7601
System Type: x64-based PC
Total Physical Memory: 4,096 MB
