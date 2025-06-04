# Port 8080 Discovery – Nmap + Python Test

stardorri 

A small recon and scanning project using Python and Nmap to identify an open HTTP service on a local host. This simulates a typical red team port discovery workflow.

---

## Target Information

- **Target IP**: `192.168.56.1`
- **Environment**: Localhost (Host-Only Virtual Network)
- **Objective**: Simulate scanning a web server and confirm service visibility

---

## Methodology

1. **Started a simple web server** on port 8080 using Python:
   ```bash
   python -m http.server 8080

## Disclaimer

This project is for educational purposes only. Do not scan IP addresses or systems you do not own or have 
explicit permission to analyze.
