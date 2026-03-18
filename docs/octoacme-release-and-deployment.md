# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Release Roles & Responsibilities
| Role | Responsibility in Release Process |
|---|---|
| Release Manager | Owns release schedule, coordinates all pre/post release activities, sends release communications |
| QA Lead | Signs off on release readiness; confirms all test plans passed |
| Project Manager | Aligns release dates with project milestones; escalates blockers |
| Developers | Merge and freeze code; support rollback if needed |
| Change Manager | Ensures stakeholder readiness; coordinates training and communication campaigns |

## Pre-release Checklist
- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] QA Lead sign-off obtained
- [ ] Release notes drafted and reviewed
- [ ] Rollback / mitigation plan documented and tested
- [ ] Smoke tests prepared and ready to run
- [ ] Stakeholders notified of upcoming release (use Release Announcement Template below)
- [ ] Support team briefed on changes and known issues

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Monitor error rates and key metrics for 24 hours post-deploy

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Announcement Template
```
Subject: [Release] <Project / Feature Name> — Version <X.Y.Z> now live

Hi <Stakeholder Group>,

We are pleased to announce the release of <Project / Feature Name>, version <X.Y.Z>,
deployed on <YYYY-MM-DD>.

What's new:
- <Notable change 1>
- <Notable change 2>

Migration steps (if any):
- <Step 1>

Known issues:
- <Issue and workaround if applicable>

Questions? Contact <Release Manager name> or open a support ticket.

Thanks,
<Release Manager>
```

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
