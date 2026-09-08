# Post-Incident Review — INC-117

**Scenario:** Delayed file processing  
**Severity:** SEV-2  
**Duration:** 09:18–10:48 (90 minutes)  
**Environment:** Fictional Arcway Cloud portfolio simulation

## Executive Summary

Multiple fictional customer accounts experienced delayed file processing. Upload acceptance and authentication remained healthy, but the processing queue accumulated work after a worker deployment reduced effective concurrency. The deployment was rolled back and recovery was validated after queue age and processing latency returned toward baseline.

## What Went Well

- Support correlated independent reports rather than treating each as an isolated account issue.
- The incident separated upload acceptance from downstream processing, narrowing the affected component.
- Customer communication avoided claiming root cause before Engineering confirmed it.
- Recovery was monitored before the incident was marked resolved.

## Opportunities

### Detection
The first operational signal came from customer reports. Queue-age alerting could identify similar degradation earlier.

### Knowledge
Support had relevant general troubleshooting guidance, but a dedicated file-processing degradation runbook would reduce investigation variance.

### Incident Linking
Related tickets should be linked to a shared incident record as soon as cross-account evidence is established.

## Corrective Actions

| Priority | Action | Intended Outcome |
|---|---|---|
| P0 | Add queue-age alert threshold and ownership | Earlier detection |
| P0 | Add worker-concurrency deployment check | Reduce regression risk |
| P1 | Publish internal processing-degradation runbook | Faster Support triage |
| P1 | Standardize incident-ticket linking | Better scope visibility |
| P2 | Review customer-facing processing guidance | Reduce unnecessary troubleshooting |

## Knowledge Feedback Loop

The incident should produce reusable knowledge: symptoms, differentiating evidence, escalation criteria and customer-safe communication. That knowledge then shortens future time-to-diagnosis.

> All details and metrics in this review are fictional portfolio material.
