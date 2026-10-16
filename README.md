# self-hosted services.

Infrastructure running 18+ containerized services on Arch Linux / NixOS with zero-trust networking via Tailscale, recursive DNS with Unbound, and automated deployment via systemd.

## services

- **Unbound DNS**: Recursive resolver, DNSSEC, local caching
- **searXNG**: Privacy-first metasearch engine
- _(16+ more containerized services)_

See `services/` for deployment configs and individual service documentation.

## stack

Docker, Docker Compose, Tailscale VPN, Unbound DNS, systemd timers, bash automation, IPv4/IPv6 dual-stack, git-based config management.

## why

Reliability through automation. Security through zero-trust networking. Portability through containers. Everything is infrastructure-as-code.

