<div align="center">
  <img src="https://github.com/M-Endymion/powershell-sccm/blob/main/thumbnail.png" alt="PowerShell SCCM Portfolio" width="100%" />
</div>

<br>

# PowerShell SCCM / MECM Scripts

A collection of PowerShell scripts for Microsoft Endpoint Configuration Manager (MECM/SCCM).

Includes client health tools, application deployment, OS configuration, macOS support, and more.

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![MECM](https://img.shields.io/badge/MECM-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)

---

## Folder Structure

| Folder                    | Purpose                                                      |
|---------------------------|--------------------------------------------------------------|
| `scripts/App-Install`     | Application installation and uninstallation                  |
| `scripts/Client-Health`   | Client health checks and repair                              |
| `scripts/OS-Configuration`| OS settings and customization                                |
| `scripts/MacOS`           | macOS provisioning and compliance                            |
| `scripts/Ubuntu`          | Ubuntu Server quick deployment                               |
| `scripts/OSD`             | Task Sequence support                                        |
| `scripts/Tools`           | GUI tools and utilities                                      |
| `scripts/Utilities`       | General helper scripts                                       |

---

## Featured Scripts

**Client-Health**  
Modern replacement for legacy client health scripts.

**App-Install**  
- `Install-Git.ps1`, `Install-7Zip.ps1`  
- Uninstall scripts for Adobe Creative Cloud, Dell SupportAssist, New Outlook, etc.

**MacOS**  
- `MacOS-Setup-and-Compliance.ps1` — System info, Homebrew tools, Intune/Jamf readiness, and reports.

**Tools**  
- `Start-BatchInstall.ps1` (interactive installer)  
- `Start-TSRerunTool.ps1` (GUI)

**Utilities**  
- `ConvertFrom-BatchScript.ps1`  
- `Ubuntu-Server-QuickDeploy.sh`

---

## How to Use

Most scripts are meant to run in **System** context through MECM Applications or Task Sequences.  
Many support `-WhatIf`, `-Fix`, and `-Verbose` parameters.

---

## About Me

**Jason Ray (M-Endymion)**  
IT professional focused on MECM/SCCM, PowerShell automation, and hybrid endpoint management (Windows + macOS).

- **LinkedIn**: [Jason Ray](https://www.linkedin.com/in/jason-ray-mecm/)
- Open to new opportunities

**Last Updated:** May 18, 2026
