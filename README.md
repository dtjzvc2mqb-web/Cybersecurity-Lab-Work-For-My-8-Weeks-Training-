# Cybersecurity-Lab-Work-For-My-8-Weeks-Training-
This repo contains my 8-week hands-on cybersecurity &amp; ethical hacking plan, daily routine, labs, scripts and weekly deliverables
## 📚 Weekly Roadmap (check when complete)

### Week 1 — Foundations: Linux + Command Line (Kali)
- [x] Read: Linux basics & terminal navigation.
- [x] Practice commands: `ls`, `cd`, `pwd`, `cp`, `mv`, `rm`, `cat`, `less`, `head`, `tail`.
- [x] Users & perms: `chmod`, `chown`, `useradd`, `passwd`.
- [x] Processes: `ps aux`, `top`, `kill`.
- [x] Package management: `sudo apt update && sudo apt upgrade -y`.
- [x] Complete TryHackMe: Linux intro room.
- [x] Deliverable: `week1/README.md` summarizing 10 commands used.

### Week 2 — Networking Basics & Reconnaissance
- [x] Study: TCP/IP, ports, DNS, ARP.
- [x] Run: `ip a`, `ip route`, `ifconfig` (if present).
- [x] Run nmap scans: `nmap -sC -sV -p- <target>`.
- [x] Capture traffic with Wireshark.
- [x] Deliverable: `week2/nmap-report.md` and `week2/capture.pcap`.

### Week 3 — Bash & Python Scripting for Pentesting
- [ ] Learn bash scripting (vars, loops, conditions).
- [ ] Create a bash script to run nmap across IPs.
- [ ] Learn Python basics (VS Code): read/write files, subprocess.
- [ ] Push `scripts/` with 2 scripts (bash + python).
- [ ] Deliverable: `week3/scripts/README.md`.

### Week 4 — Web Security Fundamentals
- [ ] Learn HTTP methods, cookies, sessions, status codes.
- [ ] Install/configure Burp Suite Community.
- [ ] Complete PortSwigger Web Academy basic labs (XSS, SQLi).
- [ ] Deliverable: `week4/web-xss-walkthrough.md`.

### Week 5 — Enumeration & Exploitation Basics
- [ ] Service enumeration: smbclient, enum4linux, ftp checks.
- [ ] Use `searchsploit` and try simple exploits in labs.
- [ ] Deliverable: `week5/exploit-walkthrough.md`.

### Week 6 — Post-Exploitation & Defensive Awareness
- [ ] Run linpeas and learn how to read its output.
- [ ] Learn indicators of compromise and basic persistence mechanisms.
- [ ] Deliverable: `week6/ioc-checklist.md`.

### Week 7 — Web App & API Advanced Techniques
- [ ] Test auth bypass, IDOR, JWT issues, logic flaws.
- [ ] Use Burp for manual and automated testing.
- [ ] Deliverable: `week7/advanced-web-walkthrough.md`.

### Week 8 — Final Project & Portfolio
- [ ] Choose a TryHackMe/CTF machine and fully document attack chain.
- [ ] Create final write-up in `week8/final-project.md`.
- [ ] Push `cybersec-portfolio` with all scripts and notes.

---

## 🧰 Tools & Setup (check when installed)
- [ ] VirtualBox — run Kali VM  
- [ ] Kali Linux VM linked to VirtualBox (snapshot taken)  
- [ ] VS Code installed with Python extension  
- [ ] Python installed and `python --version` confirmed  
- [ ] Git installed and logged into GitHub  
- [ ] GitHub repo created and initial commit pushed  
- [ ] Browser (Chrome/Brave) with extensions: uBlock Origin, Wappalyzer, HackTools  
- [ ] Burp Suite Community (for web labs)  
- [ ] Wireshark installed (for packet capture)

---

## 📆 Daily / Weekly Routine (habit checklist)
- [ ] 1 hour — theory (video/articles)  
- [ ] 1.5–2 hours — lab practice (TryHackMe/OverTheWire)  
- [ ] 15–30 min — update GitHub notes & commit changes  
- [ ] Weekly: push deliverable & short write-up

---

## 🚀 Day-1 (Tomorrow) — Exact Steps (tick as you finish)
- [ ] Boot Kali VM in VirtualBox and take a **snapshot**.  
- [ ] Open Terminal and run:
  - [ ] `sudo apt update && sudo apt upgrade -y`
- [ ] Create workspace:
  - [ ] `mkdir -p ~/cybersec/week1 && cd ~/cybersec/week1`
- [ ] Create and run a Python test:
  - [ ] Save `test.py` with `print("Hello from Kali Python")`
  - [ ] Run: `python3 test.py`
- [ ] Start TryHackMe: join first Linux room and complete first challenge.
- [ ] Commit `day1.md` to `week1/` with commands you ran and lessons learned.

---

## 🧾 Weekly Deliverables (what to push)
- [ ] Week 1: `week1/README.md` — commands & notes  
- [ ] Week 2: `week2/nmap-report.md` + `week2/capture.pcap`  
- [ ] Week 3: `scripts/` with scripts and `week3/README.md`  
- [ ] Week 4: `week4/web-xss-walkthrough.md`  
- [ ] Week 5: `week5/exploit-walkthrough.md`  
- [ ] Week 6: `week6/ioc-checklist.md`  
- [ ] Week 7: `week7/advanced-web-walkthrough.md`  
- [ ] Week 8: `week8/final-project.md` + summary video (optional)

--
