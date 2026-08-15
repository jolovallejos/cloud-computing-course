# Laboratory Activity 3: Multi-Cloud Explorer

## Student: Jolo Castillo Vallejos
## Course/Section: BS Information Technology – [4k]

---

## Linux System Investigation Results

### Commands Used and Outputs

#### 1. Operating System
```bash
$ cat /etc/os-release
```
**Output:**
```
NAME="Ubuntu"
VERSION="20.04.6 LTS (Focal Fossa)"
ID=ubuntu
PRETTY_NAME="Ubuntu 20.04.6 LTS"
VERSION_ID="20.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
```

#### 2. System Details
```bash
$ uname -a
```
**Output:**
```
Linux play-1868131 5.4.0-204-generic #224-Ubuntu SMP Thu Mar 13 16:54:05 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux
```

#### 3. CPU Information
```bash
$ lscpu
```
**Output:**
```
Architecture:                    x86_64
CPU(s):                          4
Thread(s) per core:              1
Core(s) per socket:              4
Socket(s):                       1
Model name:                      Intel(R) Xeon(R) CPU E5-2680 v4 @ 2.40GHz
CPU MHz:                         2394.446
Virtualization type:             full
```

#### 4. Number of CPU Cores
```bash
$ nproc
```
**Output:**
```
4
```

#### 5. Memory Information
```bash
$ free -h
```
**Output:**
```
              total        used        free      shared  buff/cache   available
Mem:           7.6G        1.2G        4.2G        1.7M        2.3G        6.3G
Swap:          1.0G          0B        1.0G
```

#### 6. Disk Space
```bash
$ df -h
```
**Output:**
```
Filesystem      Size  Used Avail Use% Mounted on
overlay          40G  1.1G   40G   3% /
/dev/sda1        40G  1.1G   40G   3% /tmp/host
```

---

## Cloud Hosting Options

If this Linux server were migrated to the cloud:

| Cloud Provider | Service Name | Description |
|----------------|--------------|-------------|
| **AWS** | Amazon EC2 | Virtual machine hosting with Ubuntu support |
| **Azure** | Azure Virtual Machines | Virtual machine hosting with Ubuntu support |
| **GCP** | Google Compute Engine | Virtual machine hosting with Ubuntu support |

### Migration Notes:
- **Minimal Changes Required** - This Ubuntu server can be directly migrated using "lift and shift"
- **Compatible** - Ubuntu 20.04 LTS is supported on all three cloud platforms
- **Optimization** - Can be optimized for better performance and cost efficiency

---

## Repository Contents

| File | Description |
|------|-------------|
| `aws-research.md` | AWS platform research and features |
| `azure-research.md` | Azure platform research and features |
| `gcp-research.md` | GCP platform research and features |
| `cloud-platform-comparison.md` | Comparison table and service matching |
| `client-recommendations.md` | Recommendations for 4 client scenarios |
| `reflection.md` | Mission reflection (250-350 words) |
| `README.md` | This file - Linux investigation results |

---

## Screenshots

*[Insert screenshots of your terminal outputs here]*

1. Terminal - Operating System
2. Terminal - CPU Information
3. Terminal - Memory Information
4. Terminal - Disk Space

---

## Student Information

- **Name:** Jolo Castillo Vallejos
- **Course/Section:** BS Information Technology – [4k]
- **Date:** August 15, 2026
