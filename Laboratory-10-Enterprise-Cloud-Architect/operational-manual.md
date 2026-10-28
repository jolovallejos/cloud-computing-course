# CCM101 - Cloud Computing
## Enterprise Cloud Architecture - Operational Manual

**Project:** Secure Multi-tier Web Application
**Application Stack** WordPress + MySQL (via Docker)
**Prepared:** Jolo Vallejos
**Instructor:** Jenkielyn C. Torres
**Date:** October 2026

---

## 1. System Overview
This document serves as the operational manual for the CloudNova Enterprise Server. The infrastructure consists of a heardless Ubuntu Server VM hosted on VirtualBox, running a multi-tier containerized WordPress application secured by a UFW firewall.

### Architecture Summary:
- **Host OS:** Windows (IP: 192.168.56.1)
- **Hyperviror:** VirtualBox
- **Server OS:** Ubuntu Server 24.04.5 LTS (IP: 192.168.56.101)
- **Firewall:** UFW (Allow: Port 22, Port 8080)
- **Application:** WordPress + MySQL (Presistent Volumes)

---

## 2. Deployment Guide

### Prerequisites
- VirtualBox installed on the host machine.
- Ubuntu Server ISO.
- SSH client (Git Bash or Windows Terminal).

### Step-by-Step Deployment:
1. **SSH into the Server:**
   '''bash
   ssh cloudadmin@192.168.56.101
