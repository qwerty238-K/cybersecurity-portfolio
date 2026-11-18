---
layout: page
title: Virtual Cybersecurity Lab Setup
---

# Project 1 — Virtual Cybersecurity Lab Setup

## Objective

Build a controlled, reproducible virtual environment to practise cybersecurity and networking techniques without affecting systems outside the lab.

## Environment and Tools

- Host environment: Windows and VMware Workstation (confirm exact version).
- Virtual machines: Kali Linux and a locally controlled lab target (replace with exact target name).
- Networking: isolated host-only or other explicitly authorised lab network (confirm actual configuration).
- Verification tools: `ip addr`, `ip route`, and basic connectivity checks.

## Method — Step by Step

1. Installed and configured the hypervisor on the host computer.
2. Created the required virtual machines from trusted installation images.
3. Connected the machines to a dedicated authorised test network.
4. Checked virtual network adapters, interface addresses and routing information.
5. Tested reachability within the lab and documented the outcome.
6. Recorded screenshots and configuration notes while excluding identifying or confidential information.

> **Edit these steps to match what you actually performed.** Do not describe an isolated network if your VM settings were different.

## Results and Evidence

- **Evidence 1:** [Insert a sanitised screenshot of the virtual network configuration.]
- **Evidence 2:** [Insert a screenshot showing relevant interface addresses or topology.]
- **Evidence 3:** [Insert a screenshot showing the connectivity check and its actual result.]
- Evidence files should be placed in the `evidence/` folder, then linked here, e.g. `![Lab topology](evidence/lab-topology.png)`.

**Observed outcome:** [State whether connectivity succeeded, what was verified, and any limitation.]

## Reflection and Improvements

[Describe a real issue encountered, how you diagnosed it, and one change you would make to improve repeatability, segmentation or documentation.]

## Authorisation and Safety

All activity in this project must be restricted to systems under my control or covered by explicit authorisation. Sensitive data and host identifiers must be removed before public upload.
