# Homelab

Homelab configuration, deployment scripts, and other related things.

## Current Setup

Current setup of the homelab is still pretty simple, and can be depicted by the diagram below.

```text
Huwawei EG8145V5 (Router) ---> Dell Wyse 5070 Thin Client (thin0)
(192.168.18.1)                 (192.168.18.25, thin0.home)
```

## Future Expansion

As any homelab, there's no such thing as a perfect homelab. This part will be added with ideas to add more function to the current setup.

## Applications

Here's the list of deployed application to the homelab.

- [x] DNS server (with DoT, Ad + Malware blocking, etc)
- [ ] Observability tooling (Grafana + Prometheus)
- [ ] CI/CD server for future builds
- [ ] Home VPN, using tailscale, or something else
- [ ] ISP monitoring (speed test, ping, etc)
