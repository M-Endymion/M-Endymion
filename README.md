# [PowerShell SCCM / MECM Scripts](https://github.com/M-Endymion/powershell-sccm)

A comprehensive set of PowerShell scripts I’ve built for **Microsoft Endpoint Configuration Manager (MECM/SCCM)**. 

---

## Folder Structure

| Folder                    | Purpose                                                      |
|---------------------------|--------------------------------------------------------------|
| `scripts/App-Install`     | Application installation and uninstallation scripts          |
| `scripts/Client-Health`   | ConfigMgr client health checks, repair, and maintenance      |
| `scripts/OS-Configuration`| OS-level configuration, customization, and hardening         |
| `scripts/MacOS`           | macOS provisioning, compliance, Intune/Jamf readiness        |
| `scripts/Ubuntu`          | Ubuntu Server quick deployment (Docker, Portainer, Tailscale)|
| `scripts/OSD`             | Operating System Deployment (Task Sequence) scripts          |
| `scripts/Reporting`       | Reporting and inventory scripts                              |
| `scripts/SCCM-Automation` | Server-side automation and Status Filter Rule scripts        |
| `scripts/SCCM-Compliance` | Compliance Item (Discovery + Remediation) scripts            |
| `scripts/SCCM-Queries`    | WQL queries for collections and reports                      |
| `scripts/Tools`           | Standalone utilities and GUI tools                           |
| `scripts/Utilities`       | General purpose helper scripts                               |
| `scripts/Legacy`          | Archived/old scripts (for reference only)                    |
| `scripts/Templates`       | Script templates and best practice examples                  |

---

## Featured Folders & Scripts

### **App-Install**
- `Install-Git.ps1`, `Uninstall-Git.ps1`
- `Install-7Zip.ps1`
- `Uninstall-AdobeCreativeCloud.ps1`
- `Uninstall-DellSupportAssist.ps1`
- `Remove-NewOutlook.ps1`

### **Client-Health**
Comprehensive ConfigMgr client health & repair scripts.

### **OS-Configuration**
- `Set-PowerPlan.ps1`
- `Set-LockScreenImage.ps1`
- `Replace-Wallpaper.ps1`

### **MacOS**
- `MacOS-Setup-and-Compliance.ps1` — System info, Homebrew tools, user auditing, M365/Intune readiness, Jamf integration, and professional reports.

### **Ubuntu** (New)
- `Ubuntu-Server-QuickDeploy.sh` — Docker + Portainer + Tailscale + Watchtower + Fail2Ban for homelab servers.

### **Utilities**
- `ConvertFrom-BatchScript.ps1`
- `Search-EventLog.ps1`

### **Tools**
- `Start-TSRerunTool.ps1`
- `Start-BatchInstall.ps1`

---

## About the Author

**M-Endymion** (Jason Ray)  
IT Professional specializing in Microsoft Endpoint Configuration Manager (MECM/SCCM), PowerShell automation, and enterprise deployment solutions.

This repository serves as my **professional portfolio** showcasing production-ready scripting work for real-world enterprise environments. It also includes various personal and hobby projects (Docker, automation experiments, etc.) that reflect my continuous learning.

- **LinkedIn**: [Jason Ray](https://www.linkedin.com/in/jason-ray-mecm/)
- **GitHub Handle**: M-Endymion

---

**Last Updated:** May 07, 2026
