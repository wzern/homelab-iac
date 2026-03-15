# homelab-iac

Infrastructure-as-code for my homelab. This repo contains Docker Compose configurations organised by stack, covering self-hosted services for monitoring, tooling, proxying, version control, and CI.

## ⚠️ Security Notice

The configurations in this repo are **sanitised versions** of what is actually running. Sensitive values including credentials, tokens, internal hostnames, and network-specific configuration have been removed or replaced with placeholders.

## Stacks

| Stack | Services |
|---|---|
| `monitoring` | Gotify, Uptime Kuma, PeaNUT, Traefik |
| `tools` | Mazanoke, IT-Tools, Stirling-PDF, Omni-Tools, LubeLogger, SmokePing, CyberChef, Nginx Proxy Manager |
| `git` | Gitea, Gitea Actions Runner, Traefik |

## Structure

```
/
├── monitoring/
│   └── compose.yaml
├── foss-tools/
│   └── compose.yaml
└── gitops/
    └── compose.yaml
```
