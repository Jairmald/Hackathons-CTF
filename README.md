# Hackathons-CTF

```
  _____ _____ _____
 / ____|_   _|  ___|
| |      | | | |_
| |      | | |  _|
| |____ _| |_| |_
 \_____|_____|___|
```

<div align="center">

Cybersecurity • Challenges • Skill Building

</div>

---

## About

Hands-on CTF challenges across 7 security domains. Each challenge is realistic, structured, and designed to build offensive and defensive security skills.

---

## Categories

**Cryptography** — Ciphers, encoding, weak crypto, hash analysis

**OSINT** — Reconnaissance, metadata, social mapping, geolocation

**Log Analysis** — Event logs, SIEM, timeline reconstruction, forensics

**Network Traffic** — PCAP analysis, packet extraction, malware detection

**Reverse Engineering** — Binaries, decompiling, binary exploitation

**Password Cracking** — Hashcat, John, wordlist attacks, rule-based

**Web Exploitation** — SQLi, XSS, IDOR, RCE, auth bypass, OWASP Top 10

---

## Repository Structure

```
Hackathons-CTF/
│
├── crypto/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── files/
│   │   │   ├── cipher.txt
│   │   │   └── key.txt
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── files/
│   │   │   ├── encrypted.bin
│   │   │   └── config.json
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── files/
│       └── solution.md
│
├── osint/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── assets/
│   │   │   ├── website.html
│   │   │   └── screenshots/
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── assets/
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── assets/
│       └── solution.md
│
├── logs/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── data/
│   │   │   ├── eventlogs.evtx
│   │   │   └── access.log
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── data/
│   │   │   └── syslog
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── data/
│       └── solution.md
│
├── network/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── data/
│   │   │   ├── traffic.pcap
│   │   │   └── packets.csv
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── data/
│   │   │   └── capture.pcapng
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── data/
│       └── solution.md
│
├── reversing/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── binary/
│   │   │   ├── binary.exe
│   │   │   └── binary.x86_64
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── binary/
│   │   │   └── app.bin
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── binary/
│       └── solution.md
│
├── password-cracking/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── hashes/
│   │   │   ├── hashes.txt
│   │   │   └── wordlist.txt
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── hashes/
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── hashes/
│       └── solution.md
│
├── web-exploitation/
│   ├── challenge01/
│   │   ├── instructions.md
│   │   ├── app/
│   │   │   ├── index.html
│   │   │   ├── style.css
│   │   │   ├── app.py
│   │   │   └── docker-compose.yml
│   │   └── solution.md
│   ├── challenge02/
│   │   ├── instructions.md
│   │   ├── app/
│   │   │   ├── server.js
│   │   │   ├── package.json
│   │   │   └── docker-compose.yml
│   │   └── solution.md
│   └── challenge03/
│       ├── instructions.md
│       ├── app/
│       └── solution.md
│
├── solutions/
│   ├── crypto/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   ├── osint/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   ├── logs/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   ├── network/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   ├── reversing/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   ├── password-cracking/
│   │   ├── solution01.md
│   │   ├── solution02.md
│   │   └── solution03.md
│   └── web-exploitation/
│       ├── solution01.md
│       ├── solution02.md
│       └── solution03.md
│
├── tools/
│   ├── utils.py
│   ├── solver.sh
│   └── helpers/
│       ├── decode.py
│       └── extract.sh
│
└── README.md
```

---

## Challenge Format

Each challenge contains:

- `instructions.md` — Problem statement and objectives
- `files/` or `data/` or `app/` or `binary/` or `hashes/` — Challenge resources
- `solution.md` — Detailed walkthrough and explanation

For each challenge:
1. Read instructions.md
2. Solve the challenge
3. Check solution.md for the walkthrough
