# Fabric as Community

Fabric is not only a database, runtime, or graph.

**Fabric is community.**

A community is a living graph of people, promises, responsibilities, contributions, decisions, agreements, and trust. This repository defines how Fabric DB organizes that graph openly, safely, and transparently.

> Community is the first runtime. Governance is the first schema. Trust is the first primitive.

## Anchor: Apache CloudStack

Fabric as Community uses **Apache CloudStack as the infrastructure anchor**.

CloudStack gives the community a stable open IaaS base: compute, networking, storage orchestration, accounts, domains, projects, zones, and operational cloud primitives. Fabric builds the community, governance, trust, and agent graph on top of that base.

```text
Apache CloudStack
  -> Open IaaS anchor
  -> Zones / Accounts / Domains / Projects
  -> Kubernetes / k3s runtime layer
  -> Fabric graph
  -> Agents
  -> Community governance
```

CloudStack is the anchor because Fabric needs an open cloud substrate that can be operated by communities, service providers, labs, universities, enterprises, and regional cloud partners without depending on a hyperscaler.

## Purpose

This repo is the public operating model for the Fabric DB community.

It defines:

- how people join
- how contributors become maintainers
- how decisions are proposed and accepted
- how responsibilities are assigned
- how disputes are resolved
- how partners participate
- how community work is audited
- how trust grows through contribution
- how Apache CloudStack anchors community-owned infrastructure

## Core idea

Traditional communities are managed through chat, meetings, and informal memory.

Fabric treats community as a graph:

```text
Person -> Contribution -> Review -> Decision -> Responsibility -> Trust
```

Every meaningful community action should become a transparent, inspectable record.

## Community primitives

| Primitive | Meaning |
| --- | --- |
| Person | Human participant with identity, role, and consent |
| Contribution | Work offered to the community |
| Proposal | A change request for governance, product, docs, code, or ecosystem |
| Decision | Accepted, rejected, deferred, or escalated outcome |
| Responsibility | Ownership accepted by a person or team |
| Trust | Earned confidence based on visible contribution and behavior |
| Agreement | Explicit commitment between people, maintainers, partners, or orgs |
| Evidence | Links, logs, commits, reviews, notes, or artifacts supporting a decision |
| CloudStackZone | Community or partner-operated infrastructure zone |
| CloudStackAccount | Infrastructure account mapped to a person, org, tenant, or project |
| CloudStackProject | Shared cloud project governed by community policy |

## Operating model

```text
Idea
  -> Proposal
  -> Discussion
  -> Review
  -> Decision
  -> Responsibility
  -> Delivery
  -> Evidence
  -> Trust Update
  -> CloudStack-backed Runtime when infrastructure is needed
```

## Repository structure

```text
.
├── README.md
├── GOVERNANCE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── COMMUNITY_GRAPH.md
├── TRUST_MODEL.md
├── DECISION_PROCESS.md
├── CLOUDSTACK_ANCHOR.md
├── proposals/
│   └── README.md
├── decisions/
│   └── README.md
├── roles/
│   ├── contributor.md
│   ├── maintainer.md
│   └── partner.md
└── .github/
    └── workflows/
```

## Community values

- Open by default
- Respectful by design
- Evidence before authority
- Responsibility before privilege
- Human consent before automation
- Transparent decisions
- Reversible changes where possible
- No hidden governance
- No vendor lock-in
- No capture by one actor
- Community-operable infrastructure
- Apache CloudStack as the open IaaS anchor

## Status

This repository is the first public scaffold for Fabric as Community.

The next step is to turn community activity and CloudStack-backed infrastructure activity into a governed Fabric graph.
