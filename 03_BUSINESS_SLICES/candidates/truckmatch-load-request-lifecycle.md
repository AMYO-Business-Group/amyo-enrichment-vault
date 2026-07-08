---
type: business-slice
status: approved-for-planning
workstream: TruckMatch MVP Phase 1
migration_required: probably-no
rls_impact: high
notion_sync: yes
---

# TruckMatch Load Request Lifecycle

## User persona

Founder / operations lead.

## Trigger

A shipper/customer requests transport or the founder needs to log a load request.

## Outcome

A real load request is created, listed, transitioned, audited, and optionally linked to one private document.

## Scope

- Auth/session wiring
- Create load request
- List load requests
- Transition workflow at least twice
- Confirm business events and audit logs
- Upload one private POD document

## Non-goals

- No matching algorithm
- No driver app
- No customer portal
- No route optimization
- No automated payment settlement

## Next step

Draft implementation plan after schema/code inspection.
