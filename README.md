<div align="center">

# Knowledge Base & Incident Management

### Documentation · Incident Response · Escalation · Knowledge Operations

[![Live](https://img.shields.io/badge/Live-Vercel-18181B?style=flat-square)](https://knowledge-base-incident-management.vercel.app/)
![React](https://img.shields.io/badge/Frontend-React-4F46E5?style=flat-square)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-6D28D9?style=flat-square)
![Support](https://img.shields.io/badge/Focus-Support%20Operations-7C3AED?style=flat-square)
![Scenario](https://img.shields.io/badge/Scenario-Fictional-8B5CF6?style=flat-square)

**[→ Open Live Support Operations Workspace](https://knowledge-base-incident-management.vercel.app/)**

</div>

---

## Overview

This project simulates the **knowledge and incident operations layer of a fictional B2B SaaS support organization**. It combines searchable customer-facing and internal knowledge with incident coordination, service-status communication, severity classification, escalation guidance, runbooks and post-incident learning.

The fictional product is **Arcway Cloud**, a collaboration platform. All incidents, articles, service states, metrics and organizations are synthetic portfolio material.

> No real customer, employer, production incident or confidential operational data is represented here.

---

## Live Application

| Workspace | What it demonstrates |
|---|---|
| **Overview** | Operational health, recent knowledge, incident memory and the knowledge feedback loop |
| **Knowledge** | Search, Customer/Internal filtering, article metadata, tags and complete support articles |
| **Incident Center** | INC-117 impact, SEV-2 classification, timeline, root cause, mitigation and customer update |
| **Status** | Customer-facing service health and incident-history communication |
| **Severity** | SEV-1 through SEV-4 impact-based classification and response expectations |
| **Runbooks** | Repeatable investigation paths and an Engineering escalation evidence checklist |

---

## Fictional Incident — INC-117

The central scenario is a **SEV-2 delayed file-processing incident** affecting multiple fictional accounts. Upload acceptance and authentication remain healthy while downstream processing latency increases.

The application follows the incident from the first correlated customer signals through triage, severity classification, Engineering investigation, rollback, queue recovery, monitoring and validated resolution.

```text
09:18  Detected
09:27  Triaged
09:34  SEV-2 declared
09:42  Investigating
10:03  Root cause identified
10:14  Mitigating
10:31  Monitoring
10:48  Resolved
```

This distinction matters in technical support: the project does not treat every customer symptom as a platform outage. It demonstrates how **scope and evidence** change the working hypothesis.

---

## Knowledge Operations

The searchable Knowledge Base contains both **customer-facing** and **internal** documentation covering webhook delivery, browser sign-in loops, API rate limits, multi-customer degradation, incident communication and Engineering escalation.

The intended loop is:

```text
Customer signal
      ↓
Incident evidence
      ↓
Resolution
      ↓
Post-incident review
      ↓
Knowledge update
      ↓
Faster future support
```

---

## Incident Artifacts

The repository includes standalone operational documentation in addition to the interactive application:

- `incident/severity-framework.md` — impact-based SEV-1 → SEV-4 framework and reclassification principles.
- `incident/communication-templates.md` — Investigating, Identified, Monitoring and Resolved customer-update templates plus communication guardrails.
- `incident/post-incident-review.md` — complete fictional PIR for INC-117 with what went well, opportunities, corrective actions and knowledge feedback loop.

---

## Operating Model

```text
Customer signal / monitoring alert
              ↓
        Triage & scope
              ↓
     Severity classification
              ↓
  Incident owner + responders
              ↓
 Investigation + communication
              ↓
       Mitigation / recovery
              ↓
      Resolution validation
              ↓
 Post-incident review + KB update
```

---

## Technical Architecture

```text
React + TypeScript
├── src/App.tsx       # Interactive operations workspace
├── src/data.ts       # Synthetic KB, incident, service and severity data
├── src/styles.css    # Responsive application UI
├── incident/
│   ├── severity-framework.md
│   ├── communication-templates.md
│   └── post-incident-review.md
└── Vite              # Development and production build
```

The application is intentionally front-end and deterministic: it demonstrates **support-operations reasoning and information architecture**, not access to a production incident-management backend.

---

## Skills Demonstrated

`Knowledge Management` · `Technical Documentation` · `Incident Response` · `Severity Classification` · `Customer Communication` · `Engineering Escalation` · `Runbooks` · `Post-Incident Review` · `React` · `TypeScript`

---

## Portfolio Context

This is the sixth project in my Customer Experience / Technical Support portfolio. It focuses on a part of support work that is easy to overlook: **making knowledge reusable and making incident response structured**.

The project is intentionally positioned as a simulation rather than professional production-incident experience.

---

<div align="center">

### Sofia Lozano
Customer Experience · Technical Support · CRM & Support Operations

[GitHub Profile](https://github.com/sofialozano-cx) · [Live Project](https://knowledge-base-incident-management.vercel.app/)

</div>
