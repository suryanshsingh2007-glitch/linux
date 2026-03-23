
# Open Source Audit Project — Git

Student Name: Ruddransh Bhardwaj
Registration Number: 24BCE10011
Course: Open Source Software (OSS NGMC)
Chosen Software: Git
Date: March 2026

---

## Project Overview

This repository contains my capstone project for the Open Source Software course. The project is an audit of **Git**, a distributed version control system created by Linus Torvalds in 2005.

The audit covers the origin story, license analysis (GPL v2), philosophical values, Linux footprint, ecosystem mapping, and comparison with proprietary alternatives.

The repository also includes five shell scripts that demonstrate Linux command-line skills and automation concepts, connecting them to open source philosophy.

---

## Repository Structure

```
oss-audit-24BCE10914/
│
├── README.md                     # Complete documentation
├── scripts/                      # Shell scripts folder
│   ├── script1_system_report.sh
│   ├── script2_package_inspector.sh
│   ├── script3_disk_auditor.sh
│   ├── script4_log_analyzer.sh
│   └── script5_manifesto_gen.sh
└── report/
    └── OSS_Audit_Report.pdf
```

---

## Prerequisites / Environment Setup

### Required Operating System

* Linux (Ubuntu 20.04 / 22.04 / 24.04 recommended)

### Alternative Options

* Windows (using WSL)
* macOS (commands may vary slightly)

### Required Tools

The scripts use standard Linux utilities:
`bash, cat, grep, cut, uname, whoami, uptime, date, ls, du, awk, printf, tail, head, wc`

---

### Optional Installation (Git)

For Ubuntu/Debian:

```bash
sudo apt update
sudo apt install git
```

For Fedora/RHEL:

```bash
sudo dnf install git
```

For Arch Linux:

```bash
sudo pacman -S git
```

---

## Step-by-Step Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/amanraj947/oss-audit-24BCE10914.git
cd oss-audit-24BCE10914
```

### Step 2: Navigate to Scripts Directory

```bash
cd scripts
```

### Step 3: Make Scripts Executable

```bash
chmod +x *.sh
```

### Step 4: Verify Permissions

```bash
ls -l *.sh
```

---

## Running the Scripts

### Script 1: System Identity Report

**Command:**

```bash
./script1_system_report.sh
```

Displays system information such as distribution, kernel version, user, uptime, and date.

---

### Script 2: FOSS Package Inspector

**Command:**

```bash
./script2_package_inspector.sh
```

Checks whether Git is installed and displays version and basic details.

---

### Script 3: Disk and Permission Auditor

**Command:**

```bash
./script3_disk_auditor.sh
```

Shows directory sizes, permissions, and ownership details.

---

### Script 4: Log File Analyzer

**Command:**

```bash
sudo ./script4_log_analyzer.sh
```

Analyzes log files and counts occurrences of keywords such as "error".

---

### Script 5: Open Source Manifesto Generator

**Command:**

```bash
./script5_manifesto_gen.sh
```

Takes user input and generates a personalized open source statement.

---

## Running All Scripts

Create a file named `run_all.sh`:

```bash
#!/bin/bash

echo "Running all scripts..."

./scripts/script1_system_report.sh
./scripts/script2_package_inspector.sh
./scripts/script3_disk_auditor.sh
sudo ./scripts/script4_log_analyzer.sh
./scripts/script5_manifesto_gen.sh

echo "All scripts completed successfully."
```

Run it using:

```bash
chmod +x run_all.sh
./run_all.sh
```

---

## Troubleshooting

**Permission denied error:**

```bash
chmod +x script_name.sh
```

**Log file access issue:**
Run with `sudo`.

**Command not found:**
Install required packages using your package manager.

**Windows line ending issue:**

```bash
dos2unix *.sh
```

**Git not installed:**
Install using the commands given above.

---

## Tested Environments

* Ubuntu 22.04 — Working
* Ubuntu 20.04 — Working
* Debian 11 — Working
* Fedora 38 — Working
* CentOS 7 — Working
* Linux Mint — Working
* WSL (Ubuntu) — Working

---

## Dependencies Summary

* Script 1: uname, whoami, uptime, date
* Script 2: git, which, command
* Script 3: ls, du, awk
* Script 4: grep, tail, wc
* Script 5: read, date

---

## Author Information

Name: Ruddransh Bhardwaj
Registration Number: 24BCE10011
Course: Open Source Software (OSS NGMC)
Date of Submission: March 20, 2026
Chosen Software: Git
GitHub Username: Call-me-ruddra

---

## Repository Link

[https://github.com/amanraj947/oss-audit-24BCE10914](https://github.com/amanraj947/oss-audit-24BCE10914)

---

## Quick Start Commands

```bash
git clone https://github.com/amanraj2706/oss-audit-24BCE10914.git
cd oss-audit-24BCE10914/scripts

chmod +x *.sh

./script1_system_report.sh
./script2_package_inspector.sh
./script3_disk_auditor.sh
sudo ./script4_log_analyzer.sh
./script5_manifesto_gen.sh
```
