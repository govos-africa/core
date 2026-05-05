# GovOS — Organisational Structure & Ownership

## About GovOS

GovOS is an open-source Government Operating System designed as the national digital backbone for any sovereign nation. It is developed and maintained as a **nonprofit, community-governed project** built on a microkernel architecture providing foundational platform services — Identity, Payments, and Data Exchange — upon which government ministry applications operate as cryptographically verified plugins.

The project is publicly auditable under the **Apache License 2.0** and hosted at [github.com/govos-africa/core](https://github.com/govos-africa/core).

---

## Owning Entity

**GovOS** is a nonprofit organisation. The project is funded and stewarded by the **GovOS Sovereign Adoption Fund (GSAF)** — a fund established to source and manage public good financing for the development, adoption, and long-term sustainability of GovOS as a global digital public good.

Governance of the project is vested jointly in:

1. **The GSAF** — provides funding and strategic stewardship
2. **The GovOS Board** — provides organisational oversight and accountability
3. **The Technical Steering Committee (TSC)** — governs all software and architectural decisions

---

## Founding & Independence

GovOS was initiated by staff from [Smarty](https://home.tellsmarty.com), but it is structured as an independent nonprofit project. Smarty holds no ownership over GovOS. The project was spun out to ensure neutral, multi-stakeholder governance appropriate for national digital infrastructure adopted by sovereign governments.

---

## Technical Steering Committee (TSC)

All software decisions are governed by a **7-member Technical Steering Committee**:

| Seat | Count | Selection |
|---|---|---|
| National Technology Service (NTS) appointees | 3 | Appointed to represent sovereign interests of adopting nations |
| Elected contributor seats | 2 | Elected by active contributors (>10 merged PRs in 12 months) |
| Rotating ministry representatives | 2 | Rotating representatives from participating government ministries |

Significant architectural changes — new core APIs, cryptographic algorithm updates, modifications to the plugin permission model — require an RFC with a **14-day public comment period** and a TSC majority vote. Security-related RFCs require unanimous Security Council approval.

---

## Country Sovereignty Model

GovOS distinguishes clearly between the **core project** and **sovereign deployment instances**:

- **Core project** (owned by GovOS nonprofit / GSAF): the open-source codebase, SDK, architecture, and documentation
- **Sovereign Instance** (owned by each adopting nation): the deployment of GovOS within a country's own infrastructure, under the management of that nation's National Technology Service (NTS)

Each adopting country generates its own encryption keys inside nationally managed HSMs. No nation's NTS has access to, visibility into, or control over another nation's Sovereign Instance. Countries own their data, their keys, and their deployment — GovOS provides the shared platform underneath.

---

## Licensing

| Component | License |
|---|---|
| Public Core | Apache License 2.0 |
| Documentation | Creative Commons Attribution 4.0 (CC BY 4.0) |
| Plugin SDK | Apache License 2.0 |
| Sovereign Instance configuration | Government Restricted (per-nation) |

License file: [github.com/govos-africa/core/blob/main/LICENSE](https://github.com/govos-africa/core/blob/main/LICENSE)

---

## Contact

For governance and ownership enquiries: GovOS@tellsmarty.com
