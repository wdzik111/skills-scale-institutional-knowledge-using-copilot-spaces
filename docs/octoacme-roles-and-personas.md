# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance (QA)

### Role Summary
QA Engineers ensure product quality through testing, automation, and quality advocacy. They work closely with developers and product managers to validate features meet requirements and maintain quality standards.

### Responsibilities
- Design and execute test plans for new features
- Develop and maintain automated test suites
- Identify, document, and track defects
- Validate acceptance criteria and edge cases
- Provide quality metrics and release recommendations

### Goals
- Prevent defects from reaching production
- Improve test coverage and automation
- Reduce time to identify and resolve issues

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test result summaries
- Release readiness assessments

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with vested interest in project outcomes. They include executives, customers, partners, and internal teams affected by or dependent on the project deliverables.

### Responsibilities
- Provide input on business requirements and priorities
- Review and approve major decisions and changes
- Allocate budget and resources
- Accept final deliverables

### Goals
- Ensure projects align with business objectives
- Maximize return on investment
- Minimize business disruption

### Typical Communication
- Milestone reviews and status updates
- Decision approval requests
- Post-launch feedback and metrics reviews

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies and remove impediments to help teams deliver value efficiently. They coach teams on agile practices and ensure process adherence without micromanaging.

### Responsibilities
- Facilitate agile ceremonies (standups, sprint planning, retrospectives, demos)
- Remove blockers and shield team from distractions
- Coach team on agile principles and continuous improvement
- Track team velocity and capacity
- Escalate risks and dependencies to Project Manager

### Goals
- Maximize team productivity and autonomy
- Foster self-organizing, high-performing teams
- Continuously improve team processes and practices

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones to address individual blockers
- Coordination with PM on risks and capacity

### Key Interactions
- **With Project Managers**: Align on project timelines, escalate cross-team dependencies, and coordinate risk mitigation
- **With Product Managers**: Ensure backlog is refined and ready for sprint planning, clarify priorities
- **With Developers & QA**: Facilitate ceremonies, remove impediments, track sprint progress
- **With Stakeholders**: Demo completed work, gather feedback during sprint reviews

---

## UX Designer

### Role Summary
UX Designers advocate for user needs through research, design, and usability testing. They translate user insights into intuitive interfaces and collaborate with product and engineering to deliver user-centric solutions.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Define information architecture and interaction patterns
- Validate designs with users and stakeholders
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and increase satisfaction
- Ensure design consistency across products

### Typical Communication
- Design reviews and feedback sessions
- User research findings and personas
- Collaboration with developers on implementation

### Key Interactions
- **With Product Managers**: Translate customer feedback into design requirements, align on feature priorities
- **With Developers**: Collaborate on feasibility, provide design specs and assets, review implementations
- **With QA**: Define usability test scenarios, validate user flows
- **With Stakeholders**: Present design concepts, gather feedback on user experience

---

## Release Manager

### Role Summary
Release Managers coordinate and execute deployments across environments. They ensure releases are planned, tested, and communicated effectively to minimize risk and downtime.

### Responsibilities
- Plan release schedules and deployment windows
- Coordinate between Engineering, QA, Support, and Operations
- Manage release notes and change documentation
- Execute deployment runbooks and rollback procedures
- Monitor post-deployment health and metrics

### Goals
- Deliver zero-downtime deployments
- Reduce deployment-related incidents
- Maintain clear release visibility and communication

### Typical Communication
- Release planning meetings
- Deployment status updates
- Incident coordination during releases

### Key Interactions
- **With Project Managers**: Align release timelines with project milestones, coordinate stakeholder communication
- **With Developers**: Review merge readiness, validate deployment procedures
- **With QA**: Confirm test completion and release criteria, coordinate smoke testing
- **With Stakeholders & Support**: Communicate release schedules, provide release notes, coordinate go-live activities

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather, analyze, and document requirements to ensure delivered solutions meet stakeholder expectations.

### Responsibilities
- Elicit and document detailed business requirements
- Analyze business processes and identify improvement opportunities
- Create requirement specifications and user stories
- Validate solutions against business needs
- Trace requirements through development and testing

### Goals
- Ensure solutions align with business objectives
- Reduce rework through clear requirements
- Maximize business value delivery

### Typical Communication
- Requirements workshops and stakeholder interviews
- Detailed requirement documents and user stories
- Traceability matrices and impact assessments

### Key Interactions
- **With Product Managers**: Refine high-level vision into detailed requirements, assess business impact
- **With Stakeholders**: Conduct requirements gathering sessions, validate business needs
- **With Developers**: Clarify requirements, participate in solution design, validate implementation
- **With QA**: Define acceptance criteria, review test cases for requirement coverage
- **With Project Managers**: Provide impact analysis for scope changes, track requirement status

---

## Role Interactions & Communication Flows

### Project Initiation Phase
- **Product Manager** defines vision and success metrics
- **Business Analyst** gathers detailed requirements from stakeholders
- **Project Manager** creates project plan and identifies resource needs
- **UX Designer** conducts initial user research
- **Stakeholders** approve project charter and allocate resources

### Planning Phase
- **Product Manager** prioritizes backlog with input from Business Analyst
- **Scrum Master** facilitates sprint planning with development team
- **UX Designer** creates wireframes and design specifications
- **Project Manager** manages dependencies and risk register
- **Release Manager** defines release strategy and deployment windows

### Execution Phase
- **Scrum Master** runs daily standups and removes impediments
- **Developers** implement features following UX designs
- **QA** validates features against acceptance criteria
- **Business Analyst** validates solution against requirements
- **Project Manager** tracks progress and manages stakeholder communication

### Release Phase
- **QA** completes final testing and provides release recommendation
- **Release Manager** executes deployment plan
- **Project Manager** coordinates stakeholder communication
- **Developers** provide on-call support during release window
- **Support teams** receive release notes and training from Release Manager

### Retrospective Phase
- **Scrum Master** facilitates retrospective session
- **All team members** share feedback and lessons learned
- **Project Manager** documents improvements for future projects
- **Product Manager** reviews outcomes against success metrics

### Escalation Paths
- **Team-level issue** → Scrum Master → Project Manager
- **Technical decision** → Development Lead → Product Manager → Stakeholders
- **Requirements clarification** → Business Analyst → Product Manager → Stakeholders
- **UX concern** → UX Designer → Product Manager
- **Release risk** → Release Manager → Project Manager → Stakeholders
- **Security incident** → Follow security runbook, notify Security on-call and all relevant stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

