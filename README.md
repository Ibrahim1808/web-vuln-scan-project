# 🔒 Web Vulnerability Scanning Project – Nmap + Nikto

This project demonstrates how to perform a basic web application security assessment using open-source tools **Nmap** and **Nikto**. It simulates a real-world scenario of identifying and documenting potential vulnerabilities in a target system.

## 🧰 Tools Used

- **Nmap** – Network mapper for port scanning and service detection
- **Nikto** – Web server vulnerability scanner
- **Kali Linux** – Operating system for ethical hacking
- **Markdown/PDF** – Report writing and documentation

## 📄 Project Report

A formal PDF report was created to simulate real-world documentation for clients or stakeholders:
[Web_Security_Assessment_Nmap_Nikto.pdf](./report/Web_Security_Assessment_Nmap_Nikto.pdf)

## 📁 Folder Structure

- `scans/` – Sample outputs of Nmap and Nikto scans
- `scripts/` – Reusable Bash scripts for performing scans
- `report/` – Final PDF report
- `assets/` – Images or screenshots (if applicable)

## 🚀 How to Run the Scans

Make sure you have both tools installed in a Linux-based environment (e.g., Kali Linux).

```bash
# Run Nmap TCP scan
bash scripts/nmap_scan.sh

# Run Nikto scan
bash scripts/nikto_scan.sh
