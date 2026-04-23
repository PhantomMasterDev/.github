## Phantom Master

Private game server project. Custom backend built on .NET 8, deployed on dedicated hardware via Kubernetes.

We don't do half-measures. Every service is containerized, every config is versioned, every deployment is automated. No shared hosting, no shortcuts.

---

### What we're building

A from-scratch NosTale server that actually works the way the game was supposed to. Not a fork of a fork — a clean implementation with modern tooling.

- **Backend**: .NET 8 microservices — login, game channels, bazaar, mail, relations, scheduling
- **Data**: PostgreSQL + MongoDB + Redis
- **Infra**: K3s cluster on bare metal, Traefik ingress, cert-manager TLS
- **CI/CD**: GitHub Actions, container builds per-service, automated deployments
- **Hardware**: AMD EPYC, 192 GB ECC, NVMe storage — the server doesn't lag, ever

---

### Repos

| Repo | What it is |
|---|---|
| `server` | .NET source, Dockerfiles, K8s manifests |
| `client-files` | Game client data — dat, lang, maps |
| `server-files` | Server-side configs, raid scripts, timespace scripts |
| `server-translations` | i18n files (EN, DE, FR, PL, TR, IT, ES, CZ) |
| `website` | Landing page at [phantom-master.com](https://phantom-master.com) |

---

### The team

Small group, no bureaucracy. Everyone touches production.

---

*Built by hand, not by committee.*
