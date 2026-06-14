# Apache CloudStack Anchor

Fabric as Community uses Apache CloudStack as the open infrastructure anchor.

CloudStack is the stable IaaS substrate. Fabric is the graph of people, trust, governance, agents, and evidence above it.

## Why CloudStack

Fabric needs infrastructure that can be operated by many kinds of community actors:

- regional cloud providers
- universities and labs
- enterprises
- NGOs and public institutions
- local service providers
- community clouds
- edge operators

Apache CloudStack provides a practical open cloud base for this model.

## Layering

```text
Community
  -> Governance
  -> Fabric graph
  -> Agents
  -> Kubernetes / k3s
  -> Apache CloudStack
  -> Bare metal / virtualization / storage / network
```

## Mapping

| CloudStack primitive | Fabric community meaning |
| --- | --- |
| Zone | Community cloud region or partner-operated region |
| Pod | Physical or operational cluster boundary |
| Cluster | Compute capacity group |
| Host | Infrastructure provider resource |
| Domain | Governance or organizational boundary |
| Account | Tenant, person, organization, or project account |
| Project | Shared community initiative or delivery workspace |
| Role | Infrastructure permission boundary |
| Template | Approved workload base image |
| Service Offering | Governed compute shape |
| Disk Offering | Governed storage shape |
| Network Offering | Governed storage shape |
| Event | Evidence for audit and trust updates |

## Fabric extension

Fabric adds the missing community and governance layer:

```text
CloudStack Event -> Fabric Evidence -> Decision -> Responsibility -> Trust Update
```

Examples:

- a new project becomes a Fabric proposal
- a CloudStack account maps to a community member, partner, or tenant
- a zone maps to a community-operated region
- an event maps to evidence
- quota usage maps to accountability and cost transparency
- infrastructure operations map to trust and responsibility

## Governance rule

CloudStack provides capacity.

Fabric provides meaning, trust, and governance.

## Agent rule

Agents may observe CloudStack state, recommend action, and reconcile safe drift.

High-risk infrastructure actions require human approval.

Examples requiring approval:

- delete account
- delete project
- delete volume
- delete template
- open network access
- change domain roles
- change service offerings
- change zone capacity policy

## North star

A community should be able to operate its own cloud, govern its own data, run its own agents, and preserve its own trust graph.

Apache CloudStack anchors the cloud.

Fabric anchors the community.
