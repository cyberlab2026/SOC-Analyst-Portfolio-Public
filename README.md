# SOC Analyst L1 Portfolio

**Target role:** Entry-level SOC Analyst / Security Operations (Tier 1)  
**Portfolio type:** Self-directed labs and training exercises  
**Status:** Four projects completed; portfolio development ongoing

## About This Portfolio

This repository documents my cybersecurity learning through practical defensive-security labs. Each project demonstrates how I collect relevant evidence, examine it, distinguish observations from assumptions, and document clear analyst findings.

I am building skills in:

- Networking fundamentals: TCP/IP, ports, DNS, DHCP, ARP, NAT, and common services
- Windows event-log review and authentication-event triage
- Linux command-line fundamentals and authentication-log analysis
- Endpoint-security policy concepts and antivirus detection validation
- Basic network troubleshooting and connectivity testing
- SOC investigation notes, evidence handling, and evidence-based conclusions

**These are self-directed learning projects, not claims of production SOC experience.** Tool exposure in a lab is not the same as production administration. My conclusions are limited to the behaviour and evidence observed during each exercise.

## Project Index

| Project | What It Demonstrates | Status |
|---|---|---|
| [01 — Windows Event Log Investigation](./01-windows-event-log-investigation/README.md) | Reviewing Windows authentication events, identifying relevant fields, and documenting evidence-based findings | Completed |
| [02 — Endpoint Security Lab](./02-endpoint-security-lab/README.md) | Reviewing Sophos endpoint settings and documenting EICAR detection and cleanup | Completed |
| [03 — Basic Network Triage](./03-network-triage-lab/README.md) | Checking network configuration, gateway reachability, DNS resolution, and TCP connectivity | Completed |
| [04 — Linux Authentication Log Review](./04-linux-auth-log-review/README.md) | Reviewing Linux authentication failures and session activity while distinguishing evidence from assumptions | Completed |

## How I Document Each Lab

1. Define the objective and authorized scope.
2. Record the environment without exposing sensitive details.
3. Follow a repeatable investigation process.
4. Separate observed facts from hypotheses.
5. Document the conclusion, limitations, and next steps.
6. Include sanitized screenshots or sample data that are safe to publish.

## Evidence and Privacy

Before publishing evidence, remove unnecessary usernames, email addresses, IP addresses, internal hostnames, endpoint IDs, tenant identifiers, license information, tokens, recovery keys, and other private data.

Never publish real client data, credentials, private console details, or unapproved logs. All investigations should use systems I own or am explicitly authorized to inspect.

## Current Learning Goals

- Improve Windows authentication-event analysis.
- Build confidence in Linux authentication logs and basic triage.
- Practise concise, evidence-based incident documentation.
- Strengthen endpoint-security and network-troubleshooting fundamentals.
- Progress toward understanding SIEM workflows and SOC alert triage.

