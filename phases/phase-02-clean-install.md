# Phase 2 — Ubuntu 24.04 LTS Installation & System Initialization

## Objective

- Perform a clean installation of Ubuntu 24.04 LTS on legacy MacBook hardware to establish a Linux-based operating environment.
- Replace macOS entirely while ensuring successful system boot, user configuration, and initial OS functionality.

## Scope

- Creation and use of bootable installation media
- Full disk wipe and OS replacement
- Initial system configuration (user, hostname)
- Verification of successful OS installation and boot

## Tools Used

- Ubuntu 24.04 LTS ISO
- Balena Etcher
- SD Card (bootable media)
- MacBook Pro 2015 hardware

## Key Actions Performed

- Downloaded Ubuntu 24.04 LTS ISO from official source
- Created bootable installation media using Balena Etcher
- Booted MacBook from SD card into Ubuntu installer environment
- Performed full disk wipe, removing macOS completely
- Installed Ubuntu 24.04 LTS with default GNOME desktop environment
- Configured system identity:
  - Username: lab-user
  - Hostname: macbook-ubuntu-lab
- Completed installation and verified successful system boot into Ubuntu OS

## Key Decisions Made

- Selected full disk wipe to eliminate legacy OS conflicts and maximize available storage
- Chose Ubuntu 24.04 LTS for long-term support and stability
- Used SD card for installation media based on available hardware compatibility

## Risks / Issues Encountered

- Post-install performance concerns due to GNOME desktop environment on limited hardware (8GB RAM)
- System resource utilization higher than expected for lightweight lab environment
- Initial lack of system optimization for power management and performance tuning

## Outcomes / Results

- Ubuntu 24.04 LTS successfully installed and operational
- macOS fully removed from system
- System boot confirmed stable
- Base operating environment established for further configuration and hardening

## Evidence / Artifacts

- System boot screen confirming Ubuntu 24.04 LTS
- Desktop environment screenshots
- System configuration details (lab username and hostname)
- Installation media used (SD card with Ubuntu ISO)

## Current Status

- COMPLETE (REQUIRES POST-INSTALL OPTIMIZATION IN PHASE 3)
