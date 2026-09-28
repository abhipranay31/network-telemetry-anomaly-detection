{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Network Telemetry + Anomaly Detection (Security Lens)\
\
This project collects simple network telemetry (ping latency, connection counts, DNS/HTTP activity) from my laptop and uses machine learning (Isolation Forest) to detect anomalous network behavior. It is designed as a learning project that connects:\
\
- Computer networking fundamentals (IP, TCP/UDP, DNS, HTTP, routing, troubleshooting)\
- Cybersecurity concepts from CS50\'92s Introduction to Cybersecurity (threats, monitoring, defense)\
- Basic ML for anomaly detection\
\
## Certificates\
\
- Cisco SkillsForAll \'96 Networking Basics (in progress)\
- CS50\'92s Introduction to Cybersecurity (in progress)\
\
## Repo Structure\
\
- `collector/` \'96 Scripts to collect network telemetry (ping, netstat, traceroute, packet captures).\
- `analysis/` \'96 Jupyter notebooks for EDA, feature engineering, and anomaly detection.\
- `data/` \'96 Raw and processed telemetry data (CSV files).\
- `docs/` \'96 Notes, course summaries, and project documentation.}