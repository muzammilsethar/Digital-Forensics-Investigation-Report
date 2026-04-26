# 🔍 Digital Forensics Investigation & Memory Analysis

## 📌 Project Overview
This project demonstrates a full-scale digital forensic investigation. It simulates a professional workflow for recovering deleted data, capturing volatile memory (RAM), and extracting system registry hives.



## 🛠 Tools Used
- **FTK Imager:** Forensic imaging and RAM capture.
- **Autopsy:** Data carving and automated recovery.
- **HxD Hex Editor:** Manual byte-level verification of file headers.

## 🚀 Key Modules

### 1. Data Recovery & Carving
Recovered deleted artifacts from a logical drive and verified their integrity using Hex signatures.
![Recovery Proof](Screenshots/ram_dump_hxd.png)

### 2. Live Memory Forensics (RAM Dump)
Captured a physical memory dump to preserve volatile evidence (active processes, network connections) that would be lost upon system shutdown.
![RAM Dump](Screenshots/Ram_dump_succ.png)

### 3. Registry Forensics (SAM Extraction)
Extracted protected Windows Registry hives (SAM, SYSTEM) to facilitate offline password auditing and user account analysis.
![SAM Extraction](Screenshots/sam_prgrs.png)

## 📂 Project Structure
- `DIGITAL_FORENSICS_REPORT.pdf`: Detailed investigation report.
- `/Screenshots`: Visual evidence of tool outputs and hex analysis.

---
*Note: This investigation was performed in a controlled environment for educational purposes following forensic best practices.*
