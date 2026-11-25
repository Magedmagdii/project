# project

A reusable template for handing over IT projects to operations. Copy this checklist for each release and record the evidence your support team will need.

## Handover record

| Field | Details |
| --- | --- |
| System and version | |
| Business owner | |
| Project lead | |
| Operations owner | |
| Go-live date and time zone | |
| Support coverage and escalation contact | |
| Change ticket and runbook links | |

## Readiness checklist

Add an owner, status (Pass, Fail, or N/A), and evidence link for each check. Record exceptions before sign-off.

| Check | Acceptance criteria | Owner | Status / evidence |
| --- | --- | --- | --- |
| Business workflows | Business owner approved tests of critical workflows. | | |
| Data migration | Counts and key totals were reconciled where applicable. | | |
| Access | Users and support staff tested their assigned roles. | | |
| Backup and recovery | A recent backup was restored in a test environment. | | |
| Monitoring | A test alert reached the on-call team. | | |
| Support | The operations team can access the runbook and escalate incidents. | | |
| Rollback | The decision owner, trigger, deadline, and recovery steps are documented. | | |

## Rollback plan

- Trigger:
- Decision owner and deadline:
- Recovery steps:
- Post-rollback verification:
- User and support communications:

## Open issues

| Issue | Impact | Workaround | Owner | Target date |
| --- | --- | --- | --- | --- |
| | | | | |

## Sign-off

- Decision (Go live / Go live with exceptions / Hold):
- Accepted exceptions and owners:
- Business owner approval and date:
- Operations owner approval and date:
- First post-launch review:

## Worked example

In a fictional Odoo rollout for a printing company, the business owner tests a single order from quotation through production, delivery, and invoice. The support team verifies that warehouse users can validate deliveries and that invoice approvals stay with Finance. If completed deliveries cannot be invoiced, the release owner checks the rollback criteria before opening access to all users.
