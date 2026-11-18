---
layout: page
title: Nmap Service Scan and Analysis
---

# Project 2 — Nmap Service Scan and Analysis

## Objective

Use Nmap to discover exposed TCP ports and identify reported services on an explicitly authorised lab target, then explain the findings and limitations.

## Environment and Tools

- Attacker or analyst machine: [Kali Linux / other actual environment]
- Target: [Specify your own lab VM or authorised practice platform; anonymise sensitive identifiers]
- Network: [Describe only the authorised test network]
- Main tool: Nmap [record the actual version]

## Method — Step by Step

1. Confirmed the lab target was owned, controlled or authorised for scanning.
2. Checked the active network interface, scope and target IP address.
3. Performed an initial TCP port scan using an appropriate set of ports.
4. Ran service-version identification where permitted, for example `nmap -sV -p 22,80,443 <AUTHORISED_LAB_TARGET_IP>`.
5. Recorded the exact command, target scope, scan time, port states and service output.
6. Compared observations against the lab configuration and checked that conclusions did not exceed the evidence.

> **Replace example command and methods with those you really used.** Never scan a public or third-party host without permission.

## Results and Evidence

- **Evidence 1:** [Insert a sanitised screenshot showing the exact Nmap command.]
- **Evidence 2:** [Insert the real scan results, including port states.]
- **Evidence 3:** [Optionally include a short text result or analysis table.]
- Evidence files should be placed in `evidence/` and linked here using Markdown.

| Port / protocol | Observed state | Service identification | Interpretation |
| --- | --- | --- | --- |
| [Actual port] | [Actual state] | [Actual service] | [Evidence-based explanation] |

**Findings:** [Summarise only verified observations and acknowledge scan limitations.]

## Reflection and Improvements

[Explain at least one actual challenge, such as host reachability, unexpected service fingerprints or how you would improve repeatability.]

## Authorisation and Safety

This project demonstrates scanning of authorised targets only. No unauthorised access, credential testing or scanning of third-party networks is included.
