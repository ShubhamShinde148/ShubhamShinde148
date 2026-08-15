<div align="center">

```
██████╗ █████╗ ███████╗███████╗    ███████╗██╗██╗     ███████╗
██╔════╝██╔══██╗██╔════╝██╔════╝    ██╔════╝██║██║     ██╔════╝
██║     ███████║███████╗█████╗      █████╗  ██║██║     █████╗  
██║     ██╔══██║╚════██║██╔══╝      ██╔══╝  ██║██║     ██╔══╝  
╚██████╗██║  ██║███████║███████╗    ██║     ██║███████╗███████╗
 ╚═════╝╚═╝  ╚═╝╚══════╝╚══════╝    ╚═╝     ╚═╝╚══════╝╚══════╝
                    #HN-2026-0148 :: STATUS = ACTIVE
```

### `SUBJECT: shinde, shubham`  ·  `CLASSIFICATION: white-hat`  ·  `THREAT LEVEL: constructive`

</div>

<br/>

## `0x00` INCIDENT SUMMARY

> A SOC analyst reviewing anomalous GitHub traffic flagged this profile during a routine threat hunt. Initial triage suggested a malicious actor — deep familiarity with exploitation chains, custom VM interpreters, cipher-breaking scripts. Further analysis revealed the opposite: **every exploit exists to be documented, patched, and taught.** Case reclassified from "threat" to "asset." Investigation remains open — subject is still active.

```yaml
designation      : Shubham Shinde
role             : Cybersecurity Student · CTF Challenge Architect · Builder of HexNova
base_of_op       : Nashik, Maharashtra, India
operating_platform: hexnova.space  (cyberpunk-themed CTF competition ground)
motive           : "study how systems break, so I can build ones that don't"
```

<br/>

## `0x01` FIRST CONTACT — TERMINAL SESSION RECOVERED

```console
soc-analyst@hexnova:~$ whois shubham
[+] resolving identity...
[+] entity builds and operates HexNova — a cyberpunk CTF competition platform
[+] entity designs multi-category challenges: web / crypto / rev / stego / forensics / OSINT
[+] entity performs security testing on own infrastructure before deploying it to others
[+] entity documents everything — VAPT reports, remediation guides, solve scripts
[+] risk assessment: LOW to adversaries who patch. HIGH to adversaries who don't.
soc-analyst@hexnova:~$ _
```

<br/>

## `0x02` BEHAVIORAL MATRIX — MAPPED TACTICS & OBSERVED TECHNIQUES

*Standard threat-intel format, repurposed to document a skillset instead of an attack.*

| TACTIC (Domain) | OBSERVED TECHNIQUES | CONFIDENCE |
|---|---|:---:|
| **Initial Access — Web** | SSTI chains, IDOR, auth bypass, HTTP response manipulation | `████████░░` 80% |
| **Challenge Engineering** | Original web/crypto/rev/stego/OSINT CTF design, Docker-packaged deliverables | `█████████░` 95% |
| **Collection — Forensics/Stego** | LSB analysis, PNG chunk parsing, file carving | `██████░░░░` 60% |
| **Defense Evasion — Reverse Eng.** | Anti-debug bypass, bytecode VM tracing, esoteric-format decoding | `██████░░░░` 60% |
| **Command & Control — Networking** | TCP/IP internals, HTTP-level inspection, packet analysis | `████████░░` 80% |
| **Persistence — Linux Ops** | Kali Linux, shell scripting, system hardening | `████████░░` 80% |
| **Exfiltration — Data/SQL** | Query design, injection vectors, secure schema modeling | `██████░░░░` 60% |

<br/>

## `0x03` RECOVERED ARTIFACTS — PROJECT EVIDENCE LOG

<table>
<tr><td width="52%">

**`ARTIFACT_01 :: HEXNOVA`**
Cyberpunk-themed CTF competition platform — self-designed, self-tested, self-hosted challenge infrastructure across every major category.

</td><td>

```
hash    : self-operated
status  : LIVE
url     : hexnova.space
```

</td></tr>
<tr><td>

**`ARTIFACT_02 :: LA CASA DE PAPEL`**
Flask/Jinja2 SSTI challenge — heist narrative chained to remote code execution.

</td><td>

```
vector  : SSTI → RCE
stack   : Flask, Jinja2
diff    : Medium
```

</td></tr>
<tr><td>

**`ARTIFACT_03 :: GHOST REDIRECT`**
Data hidden inside raw HTTP 302 bodies, masked client-side via `history.replaceState()`.

</td><td>

```
vector  : HTTP internals
lesson  : trust the wire, not the render
```

</td></tr>
<tr><td>

**`ARTIFACT_04 :: OPERATION BLACK VAULT`**
Spy-themed, multi-stage clue-chained CTF built to stress-test solver persistence.

</td><td>

```
diff    : Hard
category: Web / Logic
```

</td></tr>
</table>

<br/>

## `0x04` KILL-CHAIN RECONSTRUCTION — CAREER TIMELINE

*Reframing the classic 7-stage kill chain as a growth trajectory instead of an attack path.*

```
RECON            →  Networking fundamentals, Linux internals, Kali workflows
                     ↓
WEAPONIZATION    →  Building original CTF challenges (web / crypto / rev / stego)
                     ↓
DELIVERY         →  Packaging challenges — Docker configs, solve scripts, docs
                     ↓
EXPLOITATION     →  Full VAPT engagements — including against his own platform
                     ↓
INSTALLATION     →  HexNova going live — cyberpunk-branded, production infra
                     ↓
COMMAND & CONTROL→  Running live CTF events, managing platform + player experience
                     ↓
ACTIONS ON OBJ.  →  Teaching solvers to think like attackers — and defend like engineers
```

<br/>

## `0x05` INTERCEPTED CHATTER — VERIFIED CREDENTIALS

```diff
+ Cisco     :: Networking Fundamentals
+ NPTEL     :: Cybersecurity / CS Fundamentals
! pending   :: AWS / Oracle badges — in progress
```

<br/>

## `0x06` CASE STATUS — OPEN TO COLLABORATION

```yaml
open_to:
  - Cybersecurity internships & SOC roles
  - CTF team collaborations
  - Open-source security tooling contributions
  - Bug bounty methodology exchange
currently_building:
  - HexNova challenge catalog & platform hardening
  - A 25-phase deep-dive networking course (security-angled, CTF-tool-referenced)
```

<div align="center">

<br/>

`[ EOF — case remains open, subject remains active ]`

<sub><i>hint for the curious: not every string in this file renders the same way twice.</i></sub>

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-000000?style=flat-square&logo=vercel&logoColor=00FF66)](https://cybersec-47e07.web.app)
[![HexNova](https://img.shields.io/badge/HEXNOVA-000000?style=flat-square&logo=hackthebox&logoColor=8B5CF6)](https://hexnova.space)
[![GitHub](https://img.shields.io/badge/GITHUB-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/ShubhamShinde148)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-000000?style=flat-square&logo=linkedin&logoColor=6366F1)](https://www.linkedin.com/in/shubham-shinde148)

---

*"Security isn't a feature you add — it's a mindset you build."*

</div>
