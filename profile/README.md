# 🔥 Fireball Industries — RED Team

> **We build the software that runs factory floors.** Industrial IoT infrastructure, zero-trust networking, and single-pane-of-glass dashboards for operational technology — from the edge to the cloud.

---

### What We Do

We're the IT side of Fireball Industries — software development, infrastructure, and the bridge between Information Technology and Operational Technology. Our code manages industrial systems across multiple sites, giving operators real-time visibility into everything from Kubernetes clusters to PLC controllers.

### The Stack

| Layer | What We Use |
|-------|-------------|
| **Backend** | Go · stdlib `net/http` · single-binary architecture |
| **Frontend** | Server-rendered HTML · vanilla JS · offline-first (no CDN dependencies) |
| **Infrastructure** | K3s · Rancher · Helm · Longhorn |
| **Networking** | Flux (zero-trust mesh) · ArcNET · ForgeNET |
| **Industrial** | AnvilMQ (multi-protocol broker) · OPC UA · Ignition SCADA |
| **Auth** | Azure AD SSO · OAuth2 Proxy · RBAC |
| **Data** | SQLite · PostgreSQL · InfluxDB |

### Our Core Projects

| Project | What It Does |
|---------|-------------|
| **EmberNET Industrial Dashboard** | Single-pane-of-glass web application for managing industrial IoT infrastructure across factory sites |
| **Flux** | Zero-trust mesh overlay network connecting distributed sites without VPNs or firewall punch-throughs |
| **AnvilMQ** | Multi-protocol message broker with native PLC drivers for Rockwell, Siemens, and CODESYS |
| **ForgeNET** | Network management and SD-WAN for industrial edge deployments |

### How We Work

- **Everything ships as a single Go binary** — no runtime dependencies, no framework bloat
- **Offline-first by design** — factory floors have unreliable internet; our systems work regardless
- **Zero-trust networking** — every connection is authenticated and encrypted, no implicit trust
- **GitOps workflows** — infrastructure as code, Helm charts, automated deployments via Rancher

### The Team

We're small, fast, and building real things. Our titles tell you where we are on the journey:

```
Ember Engineer → Red Team Engineer → Senior Red Team Engineer → VP → CTO
```

Embers become fire. 🔥

---

<sub>**Fireball Industries** · [fireballz.ai](https://fireballz.ai) · *We're on fire. Hopefully not literally.*</sub>
