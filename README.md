# Linux System Administration Simulation Project

A self-directed simulation to demonstrate core Linux system administration skills.  
Created to support my application for the Systems Administrator Technician role with the City of Santa Clara.

---

## What I Did

### 1. User & Shell Environment Management
- Created a new user (`testuser`) using `adduser`
- Switched between users with `su` and `su -`, and explored shell environments
- Verified correct login behavior using `$USER`, `$HOME`, and `whoami`

### 2. File Permissions & Ownership
- Created a file (`private.log`) as `testuser`
- Restricted access using `chmod 600` so only the owner could read/write
- Verified permission errors when accessing from another user
- Transferred file ownership with `chown` and confirmed access changes
- Practiced using symbolic (`+x`, `u+r`) and numeric (`600`, `755`) permission models

### 3. Installing and Managing Services
- Installed the `nginx` web server using `apt`
- Managed the service using `service nginx start/status/stop`
- Verified the server’s operation using `curl localhost` to test response
- Explored the use of `systemctl`, `service`, and basic process monitoring

### 4. Bash Scripting & Cron Automation
- Wrote a Bash script (`log_script.sh`) that logs the current timestamp
- Made the script executable with `chmod +x`
- Scheduled the script to run every minute using `crontab -e`
- Verified automated execution by observing consistent log output in `log.txt`
- Gained understanding of cron expressions (`* * * * *`, `*/5`, etc.)

---

## What I Learned

- How Linux handles users, permissions, and access control
- The difference between symbolic and numeric permission modes
- How to safely simulate a multi-user environment
- How to install, run, and verify services like nginx
- How to write basic shell scripts and automate tasks using cron
- How to resolve Git-related errors and manage version control via SSH

---

## Tools & Commands Used

- Operating System: Ubuntu via WSL2
- Shell: Bash
- User Management: `adduser`, `su`, `whoami`
- Permissions: `chmod`, `chown`, `ls -l`
- Services: `apt`, `service`, `systemctl`, `curl`
- Automation: `bash`, `crontab`, `nano`
- Version Control: `git`, `push`, `pull`, `branch -M`, SSH setup

---

## Next Steps

- Write bash scripts for log rotation and file cleanup
- Schedule multi-step jobs with cron
- Explore file sharing with user groups
- Monitor system logs using `journalctl` or `logrotate`

---

## Author

**Jasper Wu**  
UCSB Data Science Graduate | Systems and Backend Enthusiast  
GitHub: [github.com/Tancanfan](https://github.com/Tancanfan)
