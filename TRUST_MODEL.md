# Trust Model

Trust in Fabric is earned, visible, and reversible.

Trust is not popularity. Trust is not authority. Trust is a record of contribution, care, reliability, and accountability.

## Trust inputs

Trust may increase through:

- accepted contributions
- helpful reviews
- responsible issue triage
- reliable delivery
- respectful conflict handling
- clear documentation
- security-conscious behavior
- mentoring and community support

Trust may decrease through:

- harmful conduct
- repeated low-quality or reckless changes
- ignoring review feedback
- breaking commitments without communication
- unsafe security behavior
- undisclosed conflicts of interest
- abuse of privilege

## Trust levels

| Level | Meaning | Typical privilege |
| --- | --- | --- |
| L0 Observer | Learning and participating | Read, discuss |
| L1 Member | Participates constructively | Issues, discussions |
| L2 Contributor | Makes useful contributions | Pull requests, proposals |
| L3 Reviewer | Reviews responsibly | Review recommendations |
| L4 Maintainer | Owns an area | Merge, release, moderate |
| L5 Steward | Protects governance | Governance decisions |

## Trust rules

- Trust must be linked to evidence.
- Trust can go up or down.
- Trust is contextual by area.
- Trust does not remove accountability.
- Trust should not become gatekeeping.
- Trust must be appealable.

## Trust event example

```json
{
  "type": "TrustEvent",
  "person": "did:example:person",
  "area": "documentation",
  "change": "+1",
  "reason": "Accepted documentation contribution with maintainer review",
  "evidence": "https://github.com/fabric-db/comminuty/pull/1",
  "timestamp": "RFC3339"
}
```

## Human rule

Fabric may calculate trust signals, but humans remain responsible for role and privilege decisions.
