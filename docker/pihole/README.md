# Pi-hole

## Purpose
Pi-hole provides local DNS resolution and network-wide ad blocking for the homelab.
It serves as a foundational service for internal name resolution and future service discovery.

## Deployment
- Deployed as a Docker container via Portainer
- Runs on the primary Ubuntu Server VM
- Local-only access (no public exposure)

## Ports
- 53 TCP/UDP – DNS
- 8083 – Web UI (mapped from container port 80)

## Volumes
- `/etc/pihole` – Configuration and gravity database
- `/etc/dnsmasq.d` – DNS overrides and custom rules

## Notes
- Intended for internal DNS only
- Will later integrate with reverse proxy and internal service naming