# 🧠 Zero Alpha: Homelab & Cybersecurity Development Roadmap

_A progressive, skill-building journey designed to develop real-world capabilities in Linux system administration, penetration testing, infrastructure automation, and secure self-hosting through a mini PC-based lab._


## 🎯 Career Focus Areas

- Penetration Testing / Red Team Apprentice  
- Security Analyst (SOC Tier I)  
- Linux System Administration  
- DevSecOps & Infrastructure Engineering  
- Scripting & Automation Developer


## 🗓️ Weekly Progress Roadmap


### 🟩 Week 0: Initialization & Environment Setup ✅ *(In Progress & Ongoing)*
- Installed Arch Linux and Ubuntu-based distros on a mini PC
- Learned basic Linux commands (CLI navigation, `cd`, `ls`, `cp`, `mv`, `chmod`)
- Set hostname, updated system packages, and configured user accounts
- Fully installed and configured **Hyprland** window manager using **only the terminal**
- Registered on Hack The Box and explored the platform
- Initial use of `systemctl`, `nano`, `journalctl`, `htop`, `ip`, `ping`, and `ufw`
- Began experimenting with **Docker** and containers

🟡 _Note: Still revisiting basics to reinforce understanding. Fundamentals will be carried forward into all future phases._


### 🟩 Week 1: Foundational Linux Skills + First Self-Hosted Services ✅ *(Ongoing Reinforcement)*
- Practiced file permissions, `chmod`, `chown`, `groups`, and sudo privileges
- Installed Docker and ran basic containers (Alpine, Ubuntu, Nginx)
- Cloned and explored GitHub repos for self-hosted projects
- Enabled SSH and practiced connecting via LAN

🟡 _Focus remains on deepening understanding of Linux permissions, Docker volumes, and simple container management._


### 🔜 Week 2: Git & Dotfiles, Network Tools, Local Config Management
- Set up GitHub SSH key and push test commit from zero-alpha
- Begin organizing personal dotfiles (Hyprland, shell configs, aliases)
- Use `nmap`, `netstat`, `ss`, `tcpdump` for basic network visibility
- Install and explore:
  - `neofetch`, `ncdu`, `du`, `df`, `screen`, `tmux`
- Start learning basic `bash` scripting (aliases, variables, loops)


### 🔜 Week 3: Python & Automation Foundations
- Begin Python basics (print, input, data types, functions)
- Write first CLI Python tools:
  - Port scanner (using `socket` or `subprocess`)
  - System info collector (CPU, RAM, disk, IP)
- Save and commit to GitHub repo `zero-alpha-tools`
- Use `crontab` to schedule a test script


### 🔜 Week 4: Lab Infrastructure – Building a Vulnerable Network
- Deploy Kali Linux (VM or Docker)
- Deploy intentionally vulnerable apps:
  - DVWA
  - Juice Shop
  - Metasploitable2
  - bWAPP
- Connect them on a virtual network
- Start enumeration and fingerprinting with:
  - `nmap`, `nikto`, `gobuster`, `dirb`, `whatweb`


### 🔜 Week 5: Exploits, Credential Attacks & Lateral Movement
- Practice SQL injection, brute-force, and command injection
- Use:
  - `Hydra`, `sqlmap`, `John the Ripper`, `wpscan`, `Burp Suite`
- Learn about common misconfigs (SUID, cron jobs, kernel exploits)
- Begin tracking privilege escalation paths


### 🔜 Week 6: Linux Hardening & Blue Team Tools
- Configure:
  - SSH security (disable root login, key-based auth)
  - Firewall with UFW and rulesets
  - Fail2Ban for brute-force protection
- Install security tools:
  - `lynis`, `chkrootkit`, `rkhunter`
- Learn log analysis:
  - `journalctl`, `logwatch`, `auditd`

---

### 🔜 Week 7: Self-Hosting Project Sprint – 10+ Services with Docker
Deploy and configure each with persistent volumes, reverse proxy, and port configs.

| **Service**        | **Use Case**                        |
|--------------------|-------------------------------------|
| Portainer          | GUI Docker management               |
| Pi-hole            | DNS filtering & ad-blocking         |
| Nextcloud          | File sync and calendar hosting      |
| Jellyfin / Plex    | Media streaming                     |
| Gitea              | Private Git hosting                 |
| Vaultwarden        | Self-hosted password manager        |
| Heimdall / Dashy   | Web dashboard & bookmarks           |
| WireGuard / Tailscale | Secure VPN access              |
| Uptime Kuma        | Monitoring self-hosted services     |
| Grafana + Prometheus | Resource metrics & visualization |

Optional Extras:
- FreshRSS (self-hosted RSS reader)  
- Calibre-Web (ebook library)  
- Nginx Proxy Manager (easy reverse proxy with SSL)


### 🔜 Week 8: System Monitoring & Observability
- Deploy and integrate:
  - Prometheus + Grafana
  - Node Exporter
  - Netdata
- Monitor:
  - CPU, disk, network, Docker container stats
- Alert for downtime, high CPU usage, failed backups


### 🔜 Week 9: Red Team Simulation – Attack Chain Practice
- Simulate:
  - Enumeration
  - Foothold (e.g., RCE via HTTP)
  - Privilege escalation
  - Credential dumping
  - Persistence (SSH keys, cron jobs)
- Document chain like a real pentest report
- Tools:
  - `BloodHound`, `Responder`, `CrackMapExec`, `Netcat`


### 🔜 Week 10: Documentation, Portfolio & Public Sharing
- Organize GitHub:
  - `scripts/` → Bash & Python tools
  - `labs/` → Pentest reports and notes
  - `configs/` → Docker Compose, dotfiles
- Add markdown documentation (`README.md`) per project
- Optional:
  - Create a GitHub Pages site
  - Blog via Jekyll, Hugo, or Obsidian Publish


## 🧠 Core Technologies Covered
- Linux (Arch, Debian, Ubuntu Server)
- CLI Tools: `bash`, `systemd`, `journalctl`, `crontab`
- Git & GitHub workflows
- Docker & Docker Compose
- Python scripting
- Networking tools (SSH, Netcat, nmap, tcpdump)
- Web services & reverse proxy (Nginx)
- Offensive security tools
- Log analysis & auditing
- Monitoring stack (Grafana, Prometheus, Netdata)


## 🎯 Role Alignment Matrix

| **Skill Area**              | **Aligned Roles**                    |
|-----------------------------|--------------------------------------|
| Linux admin & scripting     | Junior Sysadmin, Infrastructure Tech |
| Docker, Nginx, self-hosting | DevOps, Platform Engineer            |
| Pentesting tools & methods  | Security Analyst, Red Team Intern    |
| Logs, firewalls, hardening  | SOC Analyst, Blue Team Operator      |
| Git, documentation, GitHub  | IT Support, DevSecOps Apprentice     |


## 📅 Progress Tracker

- [x] Week 0: Initialization
- [x] Week 1: Linux + Docker Basics
- [ ] Week 2: Git + Networking Tools
- [ ] Week 3: Python Foundations
- [ ] Week 4: Vulnerable Lab Setup
- [ ] Week 5: Exploitation & Priv Esc
- [ ] Week 6: Blue Team Hardening
- [ ] Week 7: Self-Hosting Sprint
- [ ] Week 8: Monitoring & Alerts
- [ ] Week 9: Red Team Simulation
- [ ] Week 10: Documentation & Portfolio


## 🔓 License

Licensed under the MIT License.  
Fork, remix, and build your own journey.
