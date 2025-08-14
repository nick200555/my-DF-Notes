# VirusTotal Analysis Report

## 📁 File Info
- Filename: malware_sample.zip
- File inside: malware_sample.docx
- Hashes:
  - MD5: f1fd4cf59c5cfb5e4ab5fd8570889fdb
  - SHA1: 48543fec63c090153308892c3cdfc411979c4b45
  - SHA256: ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1

## 🧪 Detection
| Engine | Detection |
|--------|-----------|
| AhnLab-V3 | Malware/Win.Kryptik.C5784104 |
| AliCloud | Trojan:MSIL/Egairtigado.Gen |
| Alibaba | Trojan:MSIL/Taskun.cf3a01e2 |
| AVG | Win32:MalwareX-gen [Pws] |
| Avira (no cloud) | TR/AD.SnakeStealer.lzrbr |


## 📡 Network Indicators
- Domains, IPs flagged

[%20DESKTOP-ET51AJO%20Clicked%20on%20the%20File%20If%20you%20see%20nothing%20this's%20mean%20the%20system%20storage's%20empty.%20]
[%20WALKER-PC%20Clicked%20on%20the%20File%20If%20you%20see%20nothing%20this's%20mean%20the%20system%20storage's%20empty.%20]



api.telegram.org
dyndns.org
reallyfreegeoip.org

104.21.112.1
104.21.16.1
104.21.32.1
104.21.48.1
104.21.64.1
104.21.80.1
104.21.96.1
132.226.247.73
132.226.8.169
149.154.167.220


## 📊 Behavioral Summary
Executes a malicious executable from the user’s desktop.
Uses PowerShell to add a Windows Defender exclusion, evading detection.
Creates multiple system processes to mimic legitimate Windows activity.
Interacts with Windows Defender components and critical system directories.
Stores malicious activity logs in hidden application data folders.
Manipulates AppRepository and cache databases to conceal its presence.

## 🗣 Community Insight
- Votes: 36/94 engines flagged as malicious.  
- User comments: Flags indicate info-stealer behavior, Telegram C2 usage, suspicious .NET obfuscation.


## 🔐 Public Link
- https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1/relations 

## 🖼 Screenshots
Include screenshots of your logged-in VT dashboard and scan results.