# Open Source Software Audit — Visual Studio Code

## Student Details

* Name: Ashwin Goyal
* Registration No.: 24BCE10596

## Chosen Software

Visual Studio Code (VS Code)

## Project Overview

This repository hosts a comprehensive audit of **Visual Studio Code (VS Code)** as an Open Source Software (OSS) project. The audit delves into VS Code's core principles, licensing details, ethical implications, community ecosystem, and its footprint on Linux operating systems. 

Through a combination of detailed written reporting and practical Bash shell scripts, this project demonstrates a strong understanding of open-source philosophies, practical system administration, and robust technical analysis.

---

## 📂 Repository Structure

The project is structured into documentation, reports, and executable administrative scripts:

```text
📦 oss-audit-24BCE10596
 ┣ 📂 Report
 ┃ ┗ 📜 report 24BCE10596.pdf     # Comprehensive written audit and OSS analysis
 ┣ 📂 scripts                     # Collection of Bash utility scripts
 ┃ ┣ 📜 manifesto_Ashwin.txt      # Personalized Open Source Philosophy manifesto
 ┃ ┣ 📜 script1.sh                # System Identity Report
 ┃ ┣ 📜 script2.sh                # FOSS Package Inspector
 ┃ ┣ 📜 script3.sh                # Disk and Permission Auditor
 ┃ ┣ 📜 script4.sh                # Log File Analyzer
 ┃ ┗ 📜 script5.sh                # Open Source Manifesto Generator
 ┣ 📜 LICENSE                     # Standard open-source license definitions (MIT)
 ┗ 📜 README.md                   # This documentation file
```

---

## 🔬 Scripts Breakdown

A core component of this audit involves developing custom CLI tools to inspect systems, track packages, and automate FOSS compliance checks.

| Script | Purpose | Description |
| :--- | :--- | :--- |
| **`script1.sh`** | 🖥️ **System Identity Report** | Gathers critical OS metrics including Kernel version, uptime, active user information, and underlying distro details. |
| **`script2.sh`** | 📦 **FOSS Package Inspector** | Specifically tracks the installation footprint, versioning, and file locations of VS Code (or other FOSS packages) on the host system. |
| **`script3.sh`** | 💽 **Disk & Permission Auditor** | Conducts a secure audit of critical system directories, checking file permissions and mapping out disk usage parameters. |
| **`script4.sh`** | 📜 **Log File Analyzer** | Parses large log files, isolates particular events or metrics, and identifies keyword occurrence frequencies for system security checking. |
| **`script5.sh`** | ✍️ **Manifesto Generator** | Dynamically constructs a personalized Open Source philosophy statement, generating a unique manifesto based on dynamic parameters. |

---

## 🚀 Getting Started

To utilize the scripts provided in this repository, you'll need a Linux environment and basic Bash proficiency.

### Prerequisites

* A Linux distribution (Tested on Ubuntu / Linux Mint)
* The GNU Bash shell (Bourne Again SHell)
* Minimum read/execute permissions on the cloned directory

### Execution Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/let-the-dreamers-rise/oss-audit-24BCE10596.git
   cd oss-audit-24BCE10596/scripts
   ```

2. **Grant execution permissions to the scripts:**
   ```bash
   chmod +x script*.sh
   ```

3. **Run any chosen script:**
   ```bash
   ./script1.sh
   ```
   *(Replace `script1.sh` with your script of choice)*

---

## 📖 The Report

The `/Report` directory contains `report 24BCE10596.pdf`. This extensive document highlights:
- The historical origins of VS Code and its transition into an open-source monolith.
- Deep-dives into the MIT License versus proprietary Microsoft licenses (e.g., standard VS Code vs. VSCodium).
- The role of extension ecosystems and ethical considerations in telemetry & data collection.
- Comparisons against traditional IDEs and standalone editors like Neovim or GNU Emacs.

---

## 🤝 Open Source Philosophy

This project embraces the collaborative and transparent nature of the FOSS community. As stated in our generated manifesto:
> *"Open source is more than just code; it is a collaborative culture built upon the principles of transparency, shared knowledge, and accessible technology for all."* 
