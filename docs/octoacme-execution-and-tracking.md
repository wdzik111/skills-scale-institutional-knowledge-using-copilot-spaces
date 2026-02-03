# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Facilitated by Scrum Master
  - All team members share updates
- Weekly delivery sync — show progress, updates, and flagged risks
  - Led by Project Manager
  - Cross-functional team attendance
- Demo/Review at the end of each sprint or milestone
  - Facilitated by Scrum Master or Product Manager
  - Stakeholders invited to provide feedback

## Role Responsibilities During Execution

### Scrum Master
- Facilitates daily standups and sprint ceremonies
- Removes blockers and shields team from distractions
- Tracks sprint progress and velocity
- Escalates risks to Project Manager when needed

### Developers
- Implement features according to acceptance criteria
- Write tests and documentation
- Participate in code reviews
- Update task status on project board

### QA
- Execute test plans and document results
- Identify and track defects
- Validate acceptance criteria
- Provide quality metrics and feedback

### UX Designer
- Provide design assets and specifications
- Review implementation for design fidelity
- Conduct usability testing as needed
- Iterate on designs based on feedback

### Business Analyst
- Clarify requirements and business rules
- Validate solutions against business needs
- Update requirements traceability
- Support team with stakeholder questions

### Product Manager
- Clarify priorities and make trade-off decisions
- Review sprint demos and provide feedback
- Manage backlog and adjust priorities as needed
- Communicate progress to stakeholders

### Project Manager
- Track overall project progress and timeline
- Manage risk register and dependencies
- Coordinate stakeholder communication
- Remove cross-team blockers

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: Project Manager escalates to Product Manager and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues (Project Manager coordinates)
- For technical blockers: Developers → Tech Lead → Product Manager
- For requirements clarification: Business Analyst → Product Manager → Stakeholders

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
