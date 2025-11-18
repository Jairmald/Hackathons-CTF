# 🚩 Network Security CTF 🚩 

![Lab Report](https://img.shields.io/badge/Status-Completed-brightgreen)
![Framework](https://img.shields.io/badge/Framework-Red%20%26%20Blue%20Teaming-blue)
![Tools](https://img.shields.io/badge/Tools-NMAP%20%26%20Kali-orange)
![Difficulty](https://img.shields.io/badge/Difficulty-Advanced-red)
![Duration](https://img.shields.io/badge/Duration-Multi%20Day-lightblue)

---

## **1. Lab Title**

> Capture The Flag (CTF) Security Competition: Red vs Blue Team Network Defense and Exploitation

---

## **2. Purpose and Objectives**

Implement offensive and defensive cybersecurity strategies through a competitive Capture The Flag exercise. Blue team secures network infrastructure while red team attempts exploitation and reconnaissance.

**Key Learning Outcomes:**
- Harden network devices (switches, routers, AP) against unauthorized access
- Perform network reconnaissance and vulnerability scanning
- Execute DDoS attacks in controlled environment
- Design and implement flag challenges (cryptography, steganography, web-based)
- Understand attack-defense dynamics in competitive security scenarios
- Develop incident response and forensic analysis skills

---

## **3. Frameworks & Technologies**

- **Network Hardening** — Disabling unnecessary services, access control configuration
- **Offensive Security** — NMAP reconnaissance, DDoS attack execution
- **Cryptography** — Text-to-ASCII-to-HEX encoding for flag obfuscation
- **Steganography** — Image-based data hiding with exiftool exploitation
- **Web Security** — Source code analysis, password bypass mechanics
- **Cisco IOS Security** — Enable secrets, line authentication, telnet disabling

---

## **4. Tools Used**

- Cisco Router & Switch (IOS command-line)
- NMAP (network scanning and vulnerability discovery)
- Kali Linux (penetration testing framework)
- Raspberry Pi (DDoS attack platform)
- Exiftool (steganography metadata extraction)
- Text-to-ASCII/HEX converters
- Python/Bash scripting for attack automation

---

## **5. Team Structure & Roles**

**Purple Team (Offensive):**
- **Jair Maldonado** — Router/Switch reconfiguration, network exploration, DDoS execution
- **Sean Moning** — Router/Switch reconfiguration, AP configuration, DDoS coordination

**Blue Team (Defensive):**
- **Taurean Muhammad** — Flag creation (4x), router/switch hardening
- **Chance Debbs** — Documentation, network configuration, flag creation (1x)

---

## **6. Defense Strategy (Blue Team)**

- Disabled SSID broadcast to prevent network visibility
- Blocked ICMP traffic from Access Point (prevented ping reconnaissance)
- Disabled Telnet access to switch (removed remote management vulnerability)
- Secured physical network devices in server rack
- Applied strong authentication credentials across all network devices
- Configured enable secrets and line passwords with encryption

---

## **7. Attack Methodology (Red Team)**

**Phase 1: Reconnaissance**
- Exploited shared server rack location with target networks
- Identified hardwired devices connected to Team 3's internal controls
- Discovered target device IP addresses and network topology

**Phase 2: Scanning & Enumeration**
- Executed NMAP commands to identify open ports and services
- Fingerprinted network devices and operating systems
- Mapped vulnerable services and protocol implementations

**Phase 3: Exploitation**
- Coordinated DDoS attack on Team 3 using multiple platforms:
  - Jair & Sean's host computers
  - Raspberry Pi running Kali Linux
- Successfully saturated target network with traffic flood

---

## **8. Flag Implementation**

**Flag 1-2: Cryptographic Encoding**
- Text message converted to ASCII representation
- ASCII values encoded as hexadecimal
- Hidden in plaintext `.txt` file requiring format conversion to extract

**Flag 3-4: Steganography (PNG)**
- Secret message embedded in PNG image metadata
- Exploitable via exiftool command-line tool
- Requires knowledge of steganography techniques to discover

**Flag 5: Web-Based Challenge**
- Interactive password guessing game on webpage
- Flag hidden in HTML source code
- Password reset mechanism resets on incorrect attempts
- Requires source code analysis and logic comprehension

---

## **9. Results**

✅ Blue team successfully hardened all network devices
✅ Red team performed successful reconnaissance on target network
✅ DDoS attack executed and target network saturated
✅ 5 flags created with varying difficulty levels (cryptography, steganography, web)
✅ Flags packaged for distribution in compressed archive
✅ Network separation and access control principles demonstrated
✅ Offensive and defensive security techniques practically applied

**Flags Captured:** 0 (by opposing teams; internal flag creation successful)

---

## **10. Challenges & Lessons**

| Challenge | Impact | Lesson |
|-----------|--------|--------|
| Flag setup simultaneous with attack phase | Reduced team efficiency | Recommend defensive hardening complete before offensive exercises |
| Incomplete network setup by some teams | Compromised attack effectiveness | Clear prerequisites and validation needed before competition |
| ICMP blocking limited reconnaissance | Defense success | Disabling basic protocols significantly increases attack difficulty |
| Telnet access removed early | Defense success | Service minimization is effective hardening strategy |
| SSID broadcast disabled | Defense success | Network obscurity provides initial defense layer |
| Shared rack location | Attack advantage | Physical security and network segmentation critical |

---

## **11. Key Takeaways**

- **Network hardening fundamentals work:** Disabling unnecessary services (Telnet), blocking ICMP, and hiding SSIDs significantly impede reconnaissance
- **Physical access matters:** Shared server rack enabled initial network discovery; physical security is foundational
- **Reconnaissance precedes exploitation:** NMAP scanning identified targets before DDoS execution; systematic approach increases success
- **Cryptography and steganography obscure data:** Multiple encoding layers (text→ASCII→HEX, PNG metadata) require technical knowledge to extract
- **Multi-vector attacks are effective:** Coordinated DDoS from multiple platforms (hosts + Raspberry Pi) creates harder target
- **Source code analysis is critical:** Web-based flags require understanding HTML structure and application logic
- **Timing and coordination matter:** Simultaneous flag setup and attacks reduced effectiveness; proper sequencing improves outcomes
- **Preparation and prerequisites are essential:** Teams with properly configured networks are more defensible and attackable

---

## **12. Deliverables**

- **Cisco configurations:** Hardened switch/router startup configurations
- **Flag archive:** CTF Flags and Password Game zip file (5 flags)
  - 2x Cryptographic text files (ASCII-to-HEX encoding)
  - 2x Steganography PNG files (exiftool-exploitable)
  - 1x Web-based password game (HTML/JavaScript)
- **Attack documentation:** NMAP commands, DDoS attack logs, reconnaissance notes
- **Defensive configurations:** SSID hiding, ICMP filtering, Telnet disabling setup
- **Network topology:** Blue team and red team network diagrams

---

## **13. Conclusion**

This CTF security lab successfully demonstrated offensive and defensive cybersecurity fundamentals through competitive red-blue team engagement. Blue team implemented defense-in-depth strategies (network hardening, service minimization, access control) while red team executed reconnaissance and DDoS attacks using professional-grade tools (NMAP, Kali Linux, Raspberry Pi).

The project highlighted critical security principles: physical security importance, defense-in-depth effectiveness, systematic attack methodology, and the value of obscuring sensitive information through cryptography and steganography. Successfully creating and securing five flag challenges demonstrated understanding of multiple security domains while defending against coordinated attacks reinforced the importance of proper network configuration and continuous monitoring.

---

## **Team**

**Purple Team (Red):** Jair Maldonado, Sean Moning  
**Blue Team (Defense):** Taurean Muhammad, Chance Debbs

---

**Lab Completed:** [Completion Date] | **Competition Status:** Active Defense
