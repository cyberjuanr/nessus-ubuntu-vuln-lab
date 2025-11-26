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


---

## Screenshots Added
- ubuntu-update-finished.png

- ## Lessons Learned
- Parallels Desktop provides a smooth virtualization experience for security labs
- Ubuntu package updates can be large and take several minutes, especially after fresh installation
- The terminal logs provide important evidence for remediation steps later in the lab
- No sensitive data was exposed in update logs; safe to upload to GitHub without blurring
- Documentation flows better when screenshots are organized by step and stored in dedicated subfolders

---

## Next Steps
- Download & install Nessus Essentials (Linux .deb package)
- Start Nessus service and complete product activation
- Configure initial scan targeting the Ubuntu VM IP
- Capture Nessus installation and setup screenshots
- Begin “Initial Vulnerability Scan” phase


