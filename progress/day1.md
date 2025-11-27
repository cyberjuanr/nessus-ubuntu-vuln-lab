# Day 1 Progress – Ubuntu Vulnerability Scanning Lab (Nessus Essentials)

## Tasks Completed
- Launched Parallels Desktop and booted Ubuntu 24.04 VM
- Opened Ubuntu terminal and verified system version/desktop environment
- Ran full system update using:
  - `sudo apt update && sudo apt upgrade -y`
- Verified successful package installation and upgrade logs
- Confirmed VM is operational and ready for Nessus installation
- Captured initial environment screenshots for documentation
- Retrieved Ubuntu VM IP address (`10.211.55.7`) using the `ip a` command for Nessus targeting
- Installed Nessus Essentials on Ubuntu using dpkg
- Entered activation code for Nessus Essentials
- Started Nessus Essentials installation and plugin compilation
- First vulnerability scan against Ubuntu VM to identify baseline vulnerabilities prior to remediation.
- Created Basic Network Scan in Nessus targeting the Ubuntu VM
- Launched and completed the initial vulnerability scan
- Collected baseline vulnerability counts (Critical, High, Medium, Low)
- Reviewed detailed vulnerability information, including CVSS scores, plugin metadata, and recommended remediation.
- Found 62 vulnerabilitiy = baseline (0 critical, 0 high, 1 medium, 0 low, and 61 informational)
- Medium vulnerability found was a false positive. This is a very common finding for Linux hosts because many services use self-signed certificates especially in a local test environment. This does not indicate a major security flaw in my Ubuntu Vm. 
- 
  





---

## Screenshots Added
- ubuntu-update-finished.png
- ubuntu-ip-address.png
- nessus-install-terminal.png
- nessus-installation-setup.png
- nessus-first-scan.png
- initial-scan-summary.png


- ## Lessons Learned
- Parallels Desktop provides a smooth virtualization experience for security labs
- Ubuntu package updates can be large and take several minutes, especially after fresh installation
- The terminal logs provide important evidence for remediation steps later in the lab
- No sensitive data was exposed in update logs; safe to upload to GitHub without blurring
- Documentation flows better when screenshots are organized by step and stored in dedicated subfolders
- Understood how Nessus identifies SSL certificate trust issues.
- Reviewed CVSS scoring and how risk factor is calculated.
- Learned how to interpret Plugin ID information and remediation guidance.
- A vulnerability scan may return zero high-severity findings if the system is secure.
- Informational findings still provide useful visibility into system configuration.
- Baseline scanning confirms that updates and default configurations minimize risk.
- Not every system will produce exploitable CVE findings—this is normal.



---

## Next Steps
- Download & install Nessus Essentials (Linux .deb package)
- Start Nessus service and complete product activation
- Configure initial scan targeting the Ubuntu VM IP
- Capture Nessus installation and setup screenshots
- Begin “Initial Vulnerability Scan” phase


