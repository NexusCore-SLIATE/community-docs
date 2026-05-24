# 🛡️ Cybersecurity & Networking Learning Path

Welcome to the Cybersecurity track. This curriculum bridges academic networking theory with actionable offensive security simulations, defensive scripting, and tool development.

## 🏁 Phase 1: Foundations & Network Mapping
Before tackling vulnerability exploitation, you must master packet mechanics and asset visibility:
* **Networking Infrastructure:** Deep diving into routing protocols, OSI layer architectures, and TCP/IP handshake states.
* **Network Mapping:** Mastering `nmap` configuration arguments to identify active hosts, open ports, and operating system fingerprints cleanly and safely:
```bash
  # Standard SYN Stealth scan with OS and version verification
  sudo nmap -sS -O -sV 192.168.1.1
