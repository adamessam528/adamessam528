# Hi, I'm Adam 👋

**Cybersecurity Engineering M.Sc. candidate at Politecnico di Torino** (graduating March 2027). Security has fascinated me since the first time I understood how a system breaks — and I've been chasing both sides of that ever since: building defenses, and taking them apart.

## What I'm working on

**Master's thesis: *Secure Network Paths* — Trusted Path Routing with TPM-based remote attestation.**

I'm making a network detect a tampered router and route around it on its own. Each router measures its own configuration into a TPM; Keylime and the neighbouring routers verify that evidence through remote attestation (Stamped Passports); and BGP (BIRD) automatically steers traffic away from any router that fails the check, with no human in the loop. I build and test it on a four-router Ubuntu testbed and measure what that trust costs in latency and overhead. Supervised by Prof. Antonio Lioy.

## Offensive security

- **[polito-ctf-writeups](https://github.com/adamessam528/polito-ctf-writeups)** — CTF write-ups from my three PoliTo security courses: **Offensive Security** (binary exploitation, web exploitation, reverse engineering), **Applied Cryptography**, and **Security Verification & Testing**. Each write-up shows the vulnerability, the reasoning, and the working exploit.

## Background

- **Teaching Assistant** for Hardware & Wireless Security at Politecnico di Torino — labs on hardware-backed security, from Trusted Execution Environments (OP-TEE) to roots of trust.
- **Security-focused intern at BookaCamp GmbH** — applied secure coding practices on a production PHP 8 / MySQL booking platform serving 3,000+ customers and 300+ staff.

**Tools:** pwntools, radare2, Burp Suite, GDB, OpenSSL, Keylime, BIRD
**Languages:** C/C++, Python, Go, JavaScript/TypeScript, PHP

---

Open to security engineering and SOC roles in Italy, across Europe, or remote. Based in Turin and authorized to work in Italy.

[LinkedIn](https://www.linkedin.com/in/adam-abdelfatah-22aaaa277/)
