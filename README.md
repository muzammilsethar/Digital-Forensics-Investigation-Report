# 🔍 Digital Forensics Investigation & Memory Analysis

## 📌 Project Overview
This comprehensive project demonstrates a professional digital forensic investigation lifecycle. It covers the acquisition and analysis of both volatile (RAM) and non-volatile (Disk) evidence using industry-standard tools.

## 🛠 Tools Used
- **FTK Imager:** Used for forensic imaging, RAM capture, and registry extraction.
- **Autopsy:** Utilized for automated data recovery and file carving.
- **HxD Hex Editor:** Employed for manual byte-level verification of file signatures and integrity checks.

## 🚀 Key Modules Covered

### 1. Data Recovery & Carving
Performed deep scanning of logical drives to recover deleted artifacts. Every recovered file was manually verified using Hex signatures (Magic Numbers) to ensure the data was not corrupted during recovery.

### 2. Live Memory Forensics (RAM Dump)
Captured a full physical memory dump to preserve volatile evidence. This process is critical for identifying active system processes, network connections, and transient data that would be lost upon system shutdown.

### 3. Registry Forensics (SAM Extraction)
Successfully extracted protected Windows Registry hives, including **SAM**, **SYSTEM**, and **SECURITY**. This establishes the foundation for offline auditing of user accounts and encrypted credential analysis.

### 4. Comparative Analysis (RAM vs. ROM)
Analyzed the fundamental differences in volatility and forensic value between RAM (Live Evidence) and ROM (Static Firmware), highlighting the importance of 'Live Response' in modern investigations.

## 📂 Project Structure
- `DIGITAL_FORENSICS_REPORT.pdf`: Complete step-by-step investigation report with technical documentation.
- `/ScreenShorts`: Technical logs and tool output captures for verification.

---
*Note: This investigation was conducted in a controlled lab environment for educational purposes following standard forensic principles.*
