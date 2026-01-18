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
- Business Analyst ensures business stakeholders understand technical progress
- Technical Writer maintains clear, accessible communication artifacts

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
- Team-level -> Scrum Master/PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- DevOps Engineer escalates infrastructure and deployment issues
- Business Analyst escalates requirements clarification and stakeholder concerns

## Role Responsibilities in Risk Management
- **Project Manager**: Owns risk register, coordinates mitigation strategies
- **Scrum Master**: Identifies and escalates team-level impediments
- **DevOps Engineer**: Monitors and mitigates infrastructure and deployment risks
- **Business Analyst**: Identifies business and requirements risks
- **All Team Members**: Report risks and contribute to mitigation plans
