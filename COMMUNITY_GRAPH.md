# Community Graph

The Fabric community is modeled as a living graph.

```text
Person -> Role -> Contribution -> Review -> Decision -> Responsibility -> Trust
```

## Why graph the community?

Communities fail when memory is informal, authority is hidden, and responsibility is unclear.

Fabric makes community work visible:

- who contributed
- who reviewed
- what was decided
- why it was decided
- who owns the next step
- what evidence supports the decision
- how trust changed over time

## Core nodes

| Node | Description |
| --- | --- |
| Person | A human participant |
| Organization | A company, foundation, partner, or public body |
| Role | Contributor, reviewer, maintainer, partner, steward |
| Contribution | Code, docs, design, issue triage, research, support, funding |
| Proposal | A structured request to change something |
| Review | Feedback or approval from a reviewer |
| Decision | Accepted, rejected, deferred, or escalated outcome |
| Responsibility | Ownership of a task, area, or promise |
| Agreement | A commitment between participants |
| Evidence | Commit, PR, issue, meeting note, artifact, test result |
| TrustEvent | A trust-impacting event |

## Core edges

| Edge | Meaning |
| --- | --- |
| `PERSON_CONTRIBUTED` | Person made a contribution |
| `CONTRIBUTION_REVIEWED_BY` | Review was performed |
| `PROPOSAL_DECIDED_AS` | Proposal reached an outcome |
| `PERSON_ACCEPTED_RESPONSIBILITY` | Person owns next action |
| `DECISION_SUPPORTED_BY` | Evidence supports the decision |
| `TRUST_UPDATED_BY` | Trust changed due to an event |
| `ORG_PARTICIPATES_IN` | Organization participates in community |
| `AGREEMENT_BINDS` | Agreement binds parties |

## JSON-LD sketch

```json
{
  "@context": "https://schema.org",
  "@type": "CreativeWork",
  "name": "Fabric Community Proposal",
  "contributor": {
    "@type": "Person",
    "name": "Contributor Name"
  },
  "about": "Fabric governance change",
  "accountablePerson": {
    "@type": "Person",
    "name": "Maintainer Name"
  }
}
```

## Rule

No privilege without responsibility.

No decision without evidence.

No trust without history.
