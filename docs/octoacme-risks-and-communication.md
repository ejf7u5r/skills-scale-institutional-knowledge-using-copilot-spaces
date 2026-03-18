# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Risk Escalation Checklist
Use this checklist when a risk meets the threshold for escalation (High impact or High likelihood):

- [ ] Risk documented in the Risk Register with ID, description, impact, likelihood, and owner
- [ ] Mitigation options assessed and documented
- [ ] Risk Manager and Project Manager notified
- [ ] Escalation notice drafted (see template below)
- [ ] Escalation sent to Product Lead or Project Sponsor as appropriate
- [ ] Response and decision recorded in the Risk Register
- [ ] Risk status updated and communicated to the team

### Risk Escalation Notice Template
```
Subject: [RISK ESCALATION] <Project Name> — <Risk ID>: <Short Description>

Risk ID: <ID>
Project: <Project Name>
Raised by: <Risk Manager / PM name>
Date: <YYYY-MM-DD>

Summary:
<One paragraph describing the risk, what triggered the escalation, and potential impact>

Impact: High / Medium / Low
Likelihood: High / Medium / Low

Proposed Mitigation Options:
1. <Option A>
2. <Option B>

Decision Needed By: <Date>
Decision Owner: <Name / Role>

Next Steps if No Decision:
<Describe default action if no response is received>
```

## Stakeholder Communication Plan Template
Use this template at the start of each project to align on communication needs across all stakeholder groups.

| Stakeholder Group | Communication Type | Frequency | Channel | Owner |
|---|---|---|---|---|
| Executive / Sponsor | Status briefing | Monthly | Email / Meeting | Project Manager |
| Engineering Team | Sprint review + standup | Weekly / Daily | Stand-up / Project board | Team Lead |
| Product & Business | Roadmap alignment | Bi-weekly | Meeting | Product Manager |
| External Partners | Milestone updates | As needed | Email | Change Manager |
| End Users | Release communications | Per release | Email / In-app | Release Manager |
| Support Team | Release notes + training | Per release | Internal wiki | Release Manager |

## Stakeholder Communication Templates

### Weekly Status Update Template
```
Subject: [Weekly Status] <Project Name> — Week of <Date>

**Status:** 🟢 On Track / 🟡 At Risk / 🔴 Blocked

Progress this week:
-

Next steps:
-

Risks & blockers:
-

Ask / decisions needed:
-
```

### Incident Communication Template
```
Subject: [INCIDENT] <Project Name> — <Short Description>

Severity: P1 / P2 / P3
Start time: <YYYY-MM-DD HH:MM UTC>
Current status: <Investigating / Mitigating / Resolved>

Triage summary:
<What happened and what is the current impact>

Actions being taken:
-

Expected resolution timeline:
<Estimated time or "Under investigation">

Post-incident blameless retrospective: Scheduled for <Date>
```
