# oss-audit-24BCY10394
# OSS Audit Project — Linux Kernel  
**Repository:** oss-audit-24BCY10394  


- **Name:** Himanshu Bafna  
- **Roll Number:** 24BCY10394  
- **Course:** Open Source Software  

---

## About the Software  
For this audit, I chose the Linux Kernel — the core of one of the most influential open-source projects in history. It falls under the Operating System Kernel category and is released under the GNU General Public License v2 (GPL v2).

---

## Scripts Description  

### 1. System Identity Report  
Displays system info like OS, kernel, uptime.

### 2. Package Inspector  
Checks if packages (firefox, linux, git) are installed.

### 3. Disk Auditor  
Shows directory permissions and size.

### 4. Log Analyzer  
Analyzes logs using keyword search.

### 5. Manifesto Generator  
Creates an open-source statement.

---

## Running the Scripts — Step by Step  

### Step 1: Open Terminal  
Open a terminal on your Linux machine (Kali or Ubuntu).

### Step 2: Go to Scripts Directory  
```bash
cd /path/to/your/scripts
```

### Step 3: Make Scripts Executable  
```bash
chmod +x script1_system_identity.sh \
script2_package_inspector.sh \
script3_disk_permission_auditor.sh \
script4_log_analyzer.sh \
script5_manifesto_generator.sh
```

### Step 4: Run the Scripts  

```bash
./script1_system_identity.sh
./script2_package_inspector.sh apache2
./script3_disk_permission_auditor.sh
./script4_log_analyzer.sh /var/log/syslog error
# On Kali Linux:
./script4_log_analyzer.sh /var/log/auth.log error
./script5_manifesto_generator.sh
```

---

## Dependencies  
- Bash  
- grep, awk, sed, df, du  
- apt (for Debian-based systems)
