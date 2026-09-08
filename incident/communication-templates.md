# Incident Communication Templates

## Investigating

**Title:** Investigating [affected capability]

We are investigating reports of [confirmed customer-visible symptom]. [Unaffected capability, if useful] remains available. Our team is assessing scope and impact. We will provide another update by [time/cadence].

## Identified

We have identified [verified cause or affected component at an appropriate level of certainty]. The team is working on [mitigation direction]. Customers may continue to experience [confirmed symptom]. The next update will be provided by [time].

## Monitoring

A mitigation has been applied and we are seeing [specific recovery signal]. We are continuing to monitor before declaring the incident resolved. [Customer action, if any].

## Resolved

Service has recovered and we have validated [recovery criterion]. The incident is resolved as of [time]. [Customer action required / No customer action is required]. We will review the incident and resulting follow-up actions internally.

## Communication Guardrails

- Do not publish an unverified hypothesis as root cause.
- State confirmed impact in customer language.
- Distinguish mitigation from validated recovery.
- Keep promised update cadence even when investigation is ongoing.
- Avoid internal jargon that does not help customers make a decision.
