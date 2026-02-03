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
- Release notes drafted by Release Manager
- Rollback / mitigation plan documented
- Smoke tests prepared by QA

## Role Responsibilities During Release

### Release Manager
- Coordinates release planning and execution
- Manages deployment runbooks and procedures
- Communicates deployment windows to stakeholders
- Executes deployment and monitors health
- Coordinates rollback if issues arise

### QA
- Completes final regression testing
- Executes smoke tests in staging and production
- Provides Go/No-Go recommendation
- Monitors for quality issues post-deployment

### Developers
- Ensure code is merge-ready and documented
- Provide on-call support during deployment window
- Assist with troubleshooting if issues arise

### Project Manager
- Communicates release status to stakeholders
- Coordinates cross-team activities
- Documents lessons learned

### Support Teams
- Review release notes and new features
- Prepare for customer inquiries
- Monitor support channels post-release

## Deployment Checklist
- [ ] Release Manager: Deployment window scheduled and communicated
- [ ] Release Manager: Deployment runbook reviewed with team
- [ ] DevOps/Release Manager: Backup or snapshot taken (if applicable)
- [ ] QA: All tests passing in staging environment
- [ ] Release Manager: Deploy to staging and coordinate smoke tests
- [ ] QA: Execute smoke tests and provide Go/No-Go decision
- [ ] Release Manager: Deploy to production (automated pipeline preferred)
- [ ] Release Manager & Developers: Run post-deploy verifications
- [ ] Release Manager: Announce release to stakeholders and support teams
- [ ] Support: Confirm receipt of release notes and training materials

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
