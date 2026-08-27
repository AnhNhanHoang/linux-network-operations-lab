# Day 2 — UTM Ubuntu Lab Setup

## Purpose

Create an isolated Ubuntu Server environment for practising Linux,
networking, system administration, and controlled troubleshooting.

## Host

- Host operating system: macOS
- Host architecture: arm64 / x86_64
- Virtualisation tool: UTM

## Virtual machine

- Name: web-server
- Guest OS: Ubuntu Server 26.04 LTS
- Architecture: arm64 / amd64
- vCPU: 2
- RAM: 2 GB / 3 GB
- Disk: 20 GB
- Network mode: Shared/NAT
- Administrative user: opsadmin

No passwords or secrets are stored in this repository.

## Verification

- Hostname: web-server
- VM boots successfully: Yes
- VM survives reboot: Yes
- Non-loopback IP assigned: Yes
- Default route exists: Yes
- DNS resolution works: Yes

Commands used:

- hostnamectl
- uname -a
- cat /etc/os-release
- lsb_release -a
- ip -br address
- ip route
- free -h
- df -h /
- getent hosts ubuntu.com

## Lifecycle

- Start: UTM Run button
- Access console: UTM VM window
- Restart: sudo reboot
- Shut down: sudo poweroff
- Clean checkpoint: web-server-clean-install clone

## Concepts learned

- The Mac is the host.
- Ubuntu is the guest operating system.
- An ISO is installation media.
- A VM is an isolated software-defined computer.
- A clean checkpoint allows a damaged lab to be recovered safely.
