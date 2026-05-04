# Phase 4 — Security Hardening

## Objective

- Establish baseline security controls on the Ubuntu system.
- Reduce exposure to unauthorized access.

## Scope

- Firewall configuration
- Basic system protection measures

## Tools Used

- UFW (Uncomplicated Firewall)

## Key Actions Performed

- Enabled UFW firewall
- Configured default rules (deny incoming, allow outgoing)
- Verified firewall status

## Key Decisions Made

- Applied default deny policy for incoming traffic
- Prioritized simplicity over advanced firewall rules

## Risks / Issues Encountered

- Risk of misconfiguration blocking legitimate traffic

## Outcomes / Results

- Firewall active and enforcing rules
- System protected from unsolicited inbound traffic

## Evidence / Artifacts

- `sudo ufw status`
- Terminal confirmation output

## Current Status

- Partial
