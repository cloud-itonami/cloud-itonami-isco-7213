# Business Model: Sheet Metal Workshop Scheduling Coordination Practice

## Classification

- Repository: `cloud-itonami-isco-7213`
- ISCO-08: `7213`
- Occupation: Sheet Metal Workers
- Social impact: worker-safety, fabrication-quality, production-continuity

## Customer

- sheet-metal fabrication shops / contractors
- independent sheet-metal fabrication crews / crew cooperatives

## Offer

- crew shift/task scheduling coordination
- task/materials-usage/progress-record logging
- sheet-metal-materials supply-order coordination
- safety-concern surfacing to shop safety officers

## Revenue

- monthly retainer
- per-crew coordination fee

## Trust Controls

- no direct finalization of a metal-cutting/forming-execution decision
  (e.g. a specific cutting or press-brake forming operation), ever
- no override of a shop safety officer's judgment, ever
- flagged safety concerns (cut hazard, machine-press hazard,
  equipment-condition concern) always route to human sign-off,
  regardless of confidence
- no supply order above the registered cost threshold without
  governor-gated human sign-off
- operating and coordination records are auditable, not editable
