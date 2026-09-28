# Network Telemetry + Anomaly Detection (Security Lens)

This project collects simple network telemetry (ping latency, connection counts, DNS/HTTP activity) from my laptop and uses machine learning (Isolation Forest) to detect anomalous network behavior. It is designed as a learning project that connects:

- Computer networking fundamentals (IP, TCP/UDP, DNS, HTTP, routing, troubleshooting)
- Cybersecurity concepts from CS50’s Introduction to Cybersecurity (threats, monitoring, defense)
- Basic ML for anomaly detection

## Certificates

- Cisco SkillsForAll – Networking Basics (in progress)
- CS50’s Introduction to Cybersecurity (in progress)

## Repo Structure

- `collector/` – Scripts to collect network telemetry (ping, netstat, traceroute, packet captures).
- `analysis/` – Jupyter notebooks for EDA, feature engineering, and anomaly detection.
- `data/` – Raw and processed telemetry data (CSV files).
- `docs/` – Notes, course summaries, and project documentation.