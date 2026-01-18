# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (monitored by DevOps Engineer)
- Release notes drafted (Technical Writer + Product Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared
- UX Designer verifies design implementation in staging
- Business Analyst validates feature meets requirements

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Update documentation with new features (Technical Writer)
- [ ] Monitor system health and error rates (DevOps Engineer)

## Release Readiness Checklist (DevOps Engineer)
Before production deployment:
- [ ] CI/CD pipeline green for all checks
- [ ] Security scans completed with no critical issues
- [ ] Infrastructure capacity validated
- [ ] Monitoring and alerting configured for new features
- [ ] Rollback procedure tested and documented
- [ ] Database migrations tested (if applicable)
- [ ] Environment variables and configurations updated
- [ ] Post-deployment verification tests prepared

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Document incident in post-mortem (Technical Writer supports)

## Role Responsibilities in Release
- **DevOps Engineer**: Executes deployment, monitors systems, manages rollback if needed
- **Developers**: Available for deployment support and hotfix development
- **Product Manager**: Coordinates release timing and stakeholder communication
- **Technical Writer**: Updates release notes and user-facing documentation
- **Project Manager**: Oversees release schedule and coordinates cross-team dependencies
- **Business Analyst**: Validates production release meets business requirements

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
