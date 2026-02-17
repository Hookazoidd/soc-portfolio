# Portfolio Overview

This portfolio is organized as investigation tickets. Each ticket shows how I document SOC Level 1 work: what triggered the review, what I checked in the logs, what evidence supports the conclusion, and what should happen next.

## Where to start
- **T001 — RDP Brute Force (Windows Event ID 4625)**  
  `tickets/T001-rdp-bruteforce/README.md`

## What each ticket includes
- **Trigger:** why the investigation started (alert or hunting)
- **Scope:** asset(s) and time window
- **Evidence:** key logs/events with timestamps + referenced screenshots
- **Checks performed:** what I verified (example: successful logons after failures)
- **Analysis:** quick correlation (source IP, user, frequency, timing)
- **Decision:** FP / TP / Suspicious, with a short justification
- **Next steps:** actions appropriate for SOC L1, including when to escalate
- **MITRE ATT&CK:** technique mapping when applicable

## Evidence and documentation standards
- Evidence files are stored in the ticket’s `evidence/` folder and referenced by filename in the write-up.
- Queries/filters used during the investigation are saved in `queries/` so the steps are reproducible.
- Potentially sensitive values are anonymized (usernames, IPs, hostnames).

## Environment notes
Environment details will be documented as the lab is finalized.
