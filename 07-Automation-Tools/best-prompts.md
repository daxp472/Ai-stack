# Best Prompts for Automation AI

10 ready-to-use prompts to build reliable automation systems.

## 1. Workflow Discovery Prompt [Beginner]
**Use case:** Identify the best process to automate first.

```text
You are an automation consultant.
My current workflow:
[DESCRIBE STEPS]
Time spent per week: [HOURS]
Pain points: [LIST]

Recommend:
- Best process to automate first
- Estimated time savings
- Required tools
- Automation complexity score
- Risk level and controls
```

## 2. Zapier Flow Designer [Intermediate]
**Use case:** Build a practical no-code automation flow.

```text
Act as a Zapier architect.
Trigger app/event: [DETAILS]
Target app/actions: [DETAILS]
Data fields: [LIST]

Create:
- Step-by-step Zap design
- Field mapping table
- Filter conditions
- Error handling path
- Test checklist
```

## 3. n8n Agent Pipeline Planner [Advanced]
**Use case:** Design developer-grade automation pipelines.

```text
You are an n8n workflow engineer.
Goal: [GOAL]
Input sources: [APIs, WEBHOOKS, FILES]
Output actions: [DESTINATIONS]

Design an n8n flow with:
- Node sequence
- Data transformation logic
- Retry and idempotency strategy
- Logging and alerting
- Security controls for secrets
```

## 4. Email Triage Automation Prompt [Beginner]
**Use case:** Auto-sort and route incoming emails.

```text
Act as an operations automation specialist.
Email categories needed: [SALES/SUPPORT/INTERNAL/etc]
Routing rules: [RULES]
Escalation conditions: [CONDITIONS]

Create:
- Classification logic
- Auto-response templates
- Task assignment rules
- Escalation workflow
- KPI dashboard suggestions
```

## 5. Lead Enrichment Workflow [Intermediate]
**Use case:** Enrich lead data automatically.

```text
You are a RevOps automation expert.
Lead source: [FORM/CRM/API]
Fields available: [FIELDS]
Fields needed: [FIELDS]

Build a workflow plan:
- Data enrichment steps
- Validation checks
- Deduplication logic
- CRM sync rules
- Compliance considerations
```

## 6. Incident Alert Runbook Generator [Advanced]
**Use case:** Build automation around incident response.

```text
Act as an SRE automation lead.
Incident type: [TYPE]
Systems affected: [SYSTEMS]
Current response process: [PROCESS]

Generate:
- Alert routing workflow
- Auto-remediation candidates
- Human approval gates
- Post-incident data capture
- Reliability metrics
```

## 7. Document Processing Pipeline [Intermediate]
**Use case:** Automate extraction from PDFs and forms.

```text
You are a document automation architect.
Document types: [INVOICES/CONTRACTS/FORMS]
Fields to extract: [LIST]
Destination system: [SYSTEM]

Design:
- Ingestion and OCR flow
- Validation rules
- Exception handling queue
- Human review trigger conditions
- Accuracy measurement plan
```

## 8. Multi-Step Agent Task Prompt [Advanced]
**Use case:** Let an agent execute bounded, multi-step work.

```text
You are an autonomous workflow agent with strict boundaries.
Objective: [OBJECTIVE]
Allowed tools: [TOOLS]
Forbidden actions: [LIST]
Success criteria: [CRITERIA]

Execute in this format:
1) Plan
2) Step-by-step execution log
3) Confidence score per step
4) Final output
5) Open risks + required human approval
```

## 9. QA Automation for Workflows [Intermediate]
**Use case:** Validate automation reliability before production.

```text
Act as an automation QA engineer.
Workflow description:
[PASTE]

Create a test plan with:
- Happy path tests
- Failure injection cases
- Data edge cases
- Retry and timeout checks
- Rollback verification

Include test data examples.
```

## 10. Automation ROI Calculator [Beginner]
**Use case:** Justify automation investment clearly.

```text
You are a business analyst.
Manual process details:
[PASTE]
Current cost: [TIME + MONEY]
Automation build/maintenance cost: [ESTIMATE]

Return:
- ROI model (3 scenarios: conservative, expected, optimistic)
- Break-even timeline
- Key assumptions
- Risks and mitigation
- Executive summary paragraph
```
