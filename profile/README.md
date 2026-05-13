<p align="center">
  <img src="banner.png" alt="Milo banner" />
</p>

## 💡 Vision & mission

Milo is an open source business operating system for product-led B2B companies. It gives you a comprehensive, Kubernetes-native system of record for your organizations, projects, users, and operations — so you can focus on building your product instead of rebuilding the same foundational infrastructure every company needs.

- **Mission**: To eliminate the undifferentiated heavy lifting that every B2B company faces when scaling operations, identity, and access management.
- **Vision**: To be the most trusted open foundation for B2B infrastructure, so that any team can ship a production-grade business platform without starting from scratch.

We believe the best infrastructure gets built collaboratively, in the open. Milo is licensed under the [AGPL](https://www.gnu.org/licenses/agpl-3.0.html) so that improvements to the foundation are shared back with the community — keeping the core strong for everyone who builds on it.

---

## 🧭 Why Milo?

If you're building a B2B product, you've almost certainly faced these problems:

- **Organizations & multi-tenancy**: Modeling customers as organizations, projects, and nested resource hierarchies is table stakes — but every team rebuilds it from scratch.
- **Identity & access**: Users, groups, roles, and policy bindings are complex to get right and painful to maintain.
- **Audit & compliance**: Who did what, when, and why — across every resource — is something regulators ask for and you never quite have.
- **Kubernetes-native operations**: Your infrastructure team already speaks Kubernetes. Your business layer should too.

Milo solves these problems with a production-ready, extensible platform so you spend your engineering time on what makes your product unique.

| Challenge | How Milo Helps |
|-----------|----------------|
| Multi-tenant resource hierarchy | First-class Organizations and Projects with automatic namespace isolation |
| Identity management at scale | Built-in Users, Groups, Roles, and PolicyBindings via a Kubernetes-style IAM API |
| Audit logging & compliance | Structured audit records across every resource operation |
| Platform extensibility | Provider framework for integrating auth (Zitadel), authorization (OpenFGA), billing, and more |
| Cross-cluster operations | Multi-cluster runtime for managing resources across infrastructure and control-plane clusters |

If you'd like to learn more, check out the [Milo repository](https://github.com/datum-cloud/milo) or visit [datum.net](https://www.datum.net).

---

## 🗂️ Services & components

Milo is a modular platform. Each service can be deployed independently or together as a full stack.

### Core platform

- [**milo**](https://github.com/milo-os/milo) — The foundation: organizations, projects, users, and access control. Start here.
- [**graphql-gateway**](https://github.com/milo-os/graphql-gateway) — One API for every resource on the platform.
- [**service-catalog**](https://github.com/milo-os/service-catalog) — A shared registry of every service on the platform — the source of truth for billing, quotas, and monitoring.

### Identity & access

- [**zitadel-provider**](https://github.com/milo-os/zitadel-provider) — User authentication and identity management, powered by Zitadel.
- [**openfga-provider**](https://github.com/milo-os/openfga-provider) — Fine-grained, relationship-based authorization, powered by OpenFGA.

### Finance & monetization

- [**billing**](https://github.com/milo-os/billing) — Tracks who pays for what — billing accounts and their links to projects.
- [**amberflo-provider**](https://github.com/milo-os/amberflo-provider) — Usage-based metering and invoicing, powered by Amberflo.
- [**ramp-provider**](https://github.com/milo-os/ramp-provider) — Keeps vendor accounting in sync with Ramp.

### Operations & reliability

- [**compliance**](https://github.com/milo-os/compliance) — Tracks third-party vendors and automates public subprocessor disclosures.
- [**fraud**](https://github.com/milo-os/fraud) — Risk scoring and fraud detection for users and transactions.
- [**incidents**](https://github.com/milo-os/incidents) — Incident management, backed by Grafana IRM.

### Networking & infrastructure

- [**bgp**](https://github.com/milo-os/bgp) — Declarative network routing via BGP, powered by GoBGP.
- [**ipam**](https://github.com/milo-os/ipam) — Allocates IP addresses and network prefixes on demand.

### Observability & activity

- [**resource-metrics**](https://github.com/milo-os/resource-metrics) — Tracks the state of every resource across every project and emits it as metrics.
- [**telemetry**](https://github.com/milo-os/telemetry) — Manages telemetry pipelines for the platform.
- [**activity**](https://github.com/milo-os/activity) — A plain-English feed of everything that's happened across your platform.

### Search & discovery

- [**search**](https://github.com/milo-os/search) — Find any resource across the platform, fast.
- [**inventory**](https://github.com/milo-os/inventory) — A complete, up-to-date view of every asset across every project.

### Communication

- [**resend-provider**](https://github.com/milo-os/resend-provider) — Transactional email delivery, powered by Resend.
- [**loops-provider**](https://github.com/milo-os/loops-provider) — Lifecycle email campaigns, powered by Loops.

---

## 🤝 Get involved

Milo is built in the open and we welcome contributors of all kinds.

- Join the conversation on [Discord](https://link.datum.net/discord) or [GitHub Discussions](https://link.datum.net/discussions).
- Follow [Datum on LinkedIn](https://www.linkedin.com/company/datum-cloud/) for updates.
- Read the [Datum blog](https://www.datum.net/blog/) for engineering deep-dives and product news.
- Open an issue or pull request in any of the repos above — we'd love to work with you.
