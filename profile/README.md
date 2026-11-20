<div align="center">

<a href="https://ciagotech.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/Ciago_Technologies_Icon_Dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/Ciago_Technologies_Icon.svg" />
    <img alt="Ciago Technologies" src="./assets/Ciago_Technologies_Icon.svg" width="96" />
  </picture>
</a>

# Ciago Technologies

**Independent Systems Infrastructure & Engineering Lab**

*Engineering bare-metal, lock-free data planes, memory runtimes, and resilient platforms for stateful software and autonomous AI.*

[![Website](https://img.shields.io/badge/Website-ciagotech.com-0F172A?style=flat-square)](https://ciagotech.com)
[![Solutions](https://img.shields.io/badge/Solutions-Architecture-1E293B?style=flat-square)](https://ciagotech.com/solutions)
[![Security](https://img.shields.io/badge/Security-Policy-0F172A?style=flat-square)](https://ciagotech.com/security)
[![License](https://img.shields.io/badge/License-Apache--2.0%20%2F%20MIT-1E293B?style=flat-square)](https://ciagotech.com)

</div>

---

## About Us

Ciago Technologies builds and operates foundational infrastructure for teams that treat their platform as a product, not a cost center. We work across the full stack—from kernel-level storage and memory primitives to multi-cluster cloud-native platforms—shipping systems that stay understandable, observable, and predictable under real-world load.

We publish our architectures, benchmarks, and recovery models openly so engineering teams can evaluate the work directly.

---

## Core Disciplines

Four disciplines, designed and operated together so nothing gets lost in handoffs:

| Discipline | Focus Areas |
| :--- | :--- |
| **Distributed Systems** | Consensus protocols (Raft / EPaxos), state machines, CRDTs, leader election, replication, and high-throughput data pipelines. |
| **Platform Engineering** | Kubernetes platforms, custom controllers & operator patterns, GitOps, multi-cluster management, internal developer platforms, and policy enforcement. |
| **Reliability Engineering** | SLO/SLI design, error budgets, chaos engineering & game days, incident response, runbook automation, and automated remediation. |
| **Security & Compliance** | Zero-trust architecture, mTLS everywhere, policy as code, supply-chain security (SLSA Level 2, SBOM generation), and continuous compliance. |

---

## Products & Open-Source Ecosystem

Our product suite is built around composable, adversarially audited systems primitives.

| Project | Category | Description | Status |
| :--- | :--- | :--- | :--- |
| **[EliteSand](https://ciagotech.com/product/elitesand/docs)** | Data Plane & AI Memory | Crash-safe Rust engine for unified actor state, persistent AI memory, and zero-copy local IPC (`io_uring`, HugeTLB, seqlocks). | Active (`v0.3.0`) |
| *More systems primitives* | *Infrastructure & Tooling* | *Additional runtimes, SDKs, and platform tooling are in active development.* | *Upcoming* |

---

## Engineering Philosophy

> **Principles that compound. No theater.**

1. **Architecture First** — ADRs, explicit invariants, and blast-radius analysis before a line of code. We model failure before we model success.
2. **Small Batches** — Incremental delivery behind feature flags, automated verification, and reversible releases. Every increment is a reviewable PR; Git history is the spec.
3. **Operate What You Build** — No proxy management and no handoffs. The engineers who design and write the system ship it to production with observability, SLOs, and rollback built in from day one.

---

## Technology Stack

- **Systems & Languages:** Rust, Go, TypeScript, Python
- **Kernel & Data Plane:** Linux, `io_uring`, HugeTLB, lock-free concurrency
- **Infrastructure & Delivery:** Kubernetes, Docker, Terraform, Ansible, Argo CD, AWS
- **Data & Observability:** PostgreSQL, Redis, Kafka, Prometheus, Grafana

---

## Security & Supply Chain

Security is built into every release pipeline:
- **Supply Chain:** SLSA Level 2 provenance, automated dependency auditing, and SBOM generation per release.
- **Responsible Disclosure:** Please **do not** open public GitHub issues for security vulnerabilities. Report them privately to **security@ciagotech.com** with reproduction steps. We acknowledge reports within 2 business days. Full policy at [ciagotech.com/security](https://ciagotech.com/security).

---

## Links & Licensing

- **Website:** [ciagotech.com](https://ciagotech.com)
- **Vision & Mission:** [ciagotech.com/what-we-think](https://ciagotech.com/what-we-think)
- **Workload Solutions:** [ciagotech.com/solutions](https://ciagotech.com/solutions)
- **Careers:** [ciagotech.com/careers](https://ciagotech.com/careers)

Unless stated otherwise in a specific repository, our open-source software is dual-licensed under **Apache-2.0 / MIT**.
