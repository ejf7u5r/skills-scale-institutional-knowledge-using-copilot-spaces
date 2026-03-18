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

## Project Sponsor

### Role Summary
The Project Sponsor provides strategic oversight, secures funding and resources, and champions the project at the executive level. They are the ultimate decision-maker for scope changes and business priority trade-offs.

### Responsibilities
- Provide strategic guidance and align the project to organizational goals
- Secure budget, resources, and executive support
- Resolve escalated issues that cannot be addressed at the PM or Product Lead level
- Approve major scope, timeline, or budget changes
- Communicate project status and value to senior leadership

### Goals
- Ensure projects deliver measurable business value
- Maintain organizational alignment and executive buy-in
- Remove high-level blockers that impede delivery

### Typical Communication
- Monthly executive briefings and milestone reviews
- Escalation calls when critical decisions are needed
- Approval emails for scope or budget changes

### Interactions with Existing Roles
- Works with **Project Manager** to define success criteria and resolve escalated risks
- Aligns with **Product Manager** on business priorities and roadmap trade-offs
- Serves as the final escalation point above the Product Lead

---

## Business Analyst

### Role Summary
The Business Analyst (BA) bridges the gap between business needs and technical solutions. They gather, document, and validate requirements to ensure the team builds the right thing.

### Responsibilities
- Conduct stakeholder interviews and requirements-gathering sessions
- Document business requirements, use cases, and acceptance criteria
- Analyze current-state processes and identify improvement opportunities
- Validate that delivered features meet business objectives
- Maintain requirements traceability throughout the project lifecycle

### Goals
- Ensure technical solutions align with business needs
- Reduce rework caused by unclear or incomplete requirements
- Accelerate decision-making with well-structured analysis

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written requirements documents, user stories, and process maps
- Collaboration in backlog refinement sessions

### Interactions with Existing Roles
- Partners with **Product Manager** to translate business needs into prioritized backlog items
- Works with **Developers** to clarify requirements and acceptance criteria during sprint planning
- Coordinates with **Project Manager** on scope and dependency tracking

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance (QA) Lead owns the testing strategy and ensures all deliverables meet defined acceptance criteria and quality standards before release.

### Responsibilities
- Design and maintain test plans, test cases, and QA processes
- Coordinate testing activities (unit, integration, regression, UAT)
- Track and report defects; ensure critical issues are resolved before release
- Define and enforce the Definition of Done for quality gates
- Champion continuous improvement of testing practices

### Goals
- Prevent defects from reaching production
- Ensure release readiness across all quality dimensions
- Build a culture of quality within the delivery team

### Typical Communication
- QA status reports and defect dashboards
- Participation in sprint reviews and release readiness reviews
- Defect triage meetings with Developers and Team Leads

### Interactions with Existing Roles
- Collaborates with **Developers** on test coverage requirements and defect resolution
- Reports release readiness status to **Release Manager** and **Project Manager**
- Works with **Business Analyst** to validate acceptance criteria are testable

---

## Release Manager

### Role Summary
The Release Manager coordinates all activities required to deploy software safely and predictably. They own the release schedule, deployment checklist, and post-release verification.

### Responsibilities
- Own the end-to-end release calendar and deployment schedule
- Coordinate pre-release gates (code freeze, testing sign-off, rollback readiness)
- Manage the deployment checklist and communicate release status to stakeholders
- Oversee post-release monitoring and handle any immediate rollback decisions
- Maintain release notes and communicate changes to internal and external audiences

### Goals
- Deliver releases on schedule with minimal production incidents
- Ensure all pre-release criteria are met before deployment
- Maintain clear release communication and documentation

### Typical Communication
- Release readiness meetings with QA Lead and engineering leads
- Release announcements to stakeholders and support teams
- Post-release incident reviews when needed

### Interactions with Existing Roles
- Coordinates with **QA Lead** on release readiness sign-off
- Works with **Project Manager** to align release dates with project milestones
- Notifies **Stakeholders** and support teams of upcoming releases and changes

---

## Change Manager

### Role Summary
The Change Manager oversees the people-side of change—ensuring teams and stakeholders are prepared, engaged, and able to adopt new processes, tools, or systems successfully.

### Responsibilities
- Assess change impact across teams and develop change management plans
- Design and deliver communication and training programs for affected stakeholders
- Monitor adoption and address resistance through targeted interventions
- Maintain a change log and track organizational readiness
- Ensure change activities are integrated into the overall project plan

### Goals
- Maximize adoption and minimize disruption during transitions
- Build stakeholder buy-in and reduce change-related resistance
- Accelerate time-to-benefit for new tools or processes

### Typical Communication
- Change impact assessments and readiness reports
- Stakeholder communication campaigns (emails, town halls, FAQs)
- Training materials and adoption dashboards

### Interactions with Existing Roles
- Aligns with **Project Manager** to embed change activities in the project schedule
- Partners with **Project Sponsor** to communicate the change vision to the organization
- Coordinates with **Business Analyst** to understand process changes and their impact on end users

---

## UI/UX Designer

### Role Summary
The UI/UX Designer is responsible for crafting intuitive, accessible, and delightful user experiences. They ensure the product is usable and that design decisions align with user needs and business goals.

### Responsibilities
- Conduct user research, usability testing, and persona development
- Create wireframes, prototypes, and high-fidelity design assets
- Define and maintain design systems and interaction patterns
- Collaborate with Developers to ensure accurate implementation of designs
- Advocate for accessibility and inclusive design standards

### Goals
- Deliver interfaces that are intuitive and meet user needs
- Reduce usability-related defects and support requests
- Ensure consistency across product surfaces through a shared design system

### Typical Communication
- Design reviews and prototype walkthroughs with stakeholders and developers
- Usability test reports and user research summaries
- Design handoff documentation and annotated mockups

### Interactions with Existing Roles
- Partners with **Business Analyst** to incorporate user research into requirements
- Works closely with **Developers** to translate designs into implemented features
- Presents design decisions to **Product Manager** for alignment with product vision

---

## Risk Manager

### Role Summary
The Risk Manager proactively identifies, assesses, monitors, and escalates project risks. They own the Risk Register and ensure mitigation plans are in place and acted upon.

### Responsibilities
- Maintain and update the project Risk Register throughout the project lifecycle
- Facilitate risk identification workshops with the delivery team and stakeholders
- Assess risk likelihood and impact; prioritize risks for mitigation
- Develop and track risk mitigation and contingency plans
- Escalate critical risks to the Project Manager and Project Sponsor
- Report risk status at weekly syncs and milestone reviews

### Goals
- Minimize the likelihood and impact of project risks
- Ensure the team is never surprised by foreseeable issues
- Build a proactive risk culture across the project team

### Typical Communication
- Weekly risk register updates and risk status reports
- Escalation notices for high-impact risks
- Risk review sessions with PM, Sponsor, and relevant leads

### Interactions with Existing Roles
- Reports critical risks to **Project Manager** and **Project Sponsor** for escalation
- Coordinates mitigation actions with **Developers**, **QA Lead**, and **Release Manager**
- Aligns with **Change Manager** on risks related to organizational change and adoption

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

