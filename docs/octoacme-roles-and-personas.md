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

## Additional Personas & Responsibilities

---

## Technical Lead / Architect

### Role Summary
Technical Leads define system architecture, set technical direction, and own major technical decisions. They bridge product requirements and implementation, ensuring systems are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Define and document system architecture and design patterns
- Set technical direction and make major architecture decisions
- Review high-impact designs and propose alternatives
- Identify technical risks and propose mitigations
- Mentor developers on technical practices and standards
- Advocate for technical debt reduction and quality initiatives

### Goals
- Ensure systems are scalable, maintainable, and performant
- Reduce rework and technical risk
- Build and maintain engineering capabilities

### Typical Communication
- Technical design reviews and architecture sessions
- One-on-ones with developers on technical growth
- Escalations to PM/Project Manager on technical trade-offs

### Interaction with Other Roles
- Works closely with **Developers** and **Product Manager** to translate product requirements into technical scope
- Escalates cross-team integration issues to **Project Manager**
- Collaborates with **DevOps / Platform Engineer** on infrastructure requirements
- Advises **Security Liaison** on architectural security considerations

---

## Delivery Lead / Technical Program Manager (TPM)

### Role Summary
Delivery Leads coordinate cross-team delivery, manage planning dependencies, and maintain release/iteration cadence. They enable efficient execution by removing blockers and tracking delivery health.

### Responsibilities
- Coordinate cross-team delivery activities and timelines
- Manage planning dependencies and integration points
- Maintain iteration/release cadence and ensure on-time delivery
- Track delivery risks and mitigations in collaboration with Project Manager
- Identify and escalate blockers affecting delivery
- Report on delivery health and progress to stakeholders

### Goals
- Maintain predictable, on-time delivery
- Minimize cross-team friction and delays
- Ensure visibility into delivery risks

### Typical Communication
- Delivery coordination meetings across teams
- Daily stand-ups and progress tracking
- Weekly status updates on delivery milestones

### Interaction with Other Roles
- Partners with **Project Manager** on timelines and scope
- Works with Engineering Managers for team capacity planning
- Collaborates with **Release Manager** to coordinate deployments
- Escalates dependencies affecting multiple teams

---

## Release Manager

### Role Summary
Release Managers own release windows, run deployment checklists, coordinate rollback plans, and validate post-deployment verification. They ensure smooth, low-risk releases to production.

### Responsibilities
- Own and schedule release windows
- Execute deployment checklists and verify pre-release requirements
- Coordinate rollback plans and mitigation strategies
- Validate post-deployment verification steps and success metrics
- Communicate release status to stakeholders and support teams
- Facilitate incident response and rollback if needed

### Goals
- Enable smooth, low-risk releases to production
- Minimize production incidents and customer impact
- Ensure rapid recovery from failures

### Typical Communication
- Pre-release coordination with technical and support teams
- Release notes and stakeholder announcements
- Post-deployment verification reports

### Interaction with Other Roles
- Works with **Delivery Lead / TPM** on release scheduling
- Collaborates with **DevOps / Platform Engineer** on deployment execution
- Coordinates with **QA/Testing** on smoke test validation
- Communicates with **Support / Customer Success** on customer impact
- Escalates critical issues to **Project Manager** and **Product Manager**

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, infrastructure as code, monitoring, and operational runbooks. They enable reliable, automated deployment and observability across systems.

### Responsibilities
- Maintain and improve CI/CD pipelines and automation
- Implement infrastructure as code and configuration management
- Set up monitoring, alerting, and logging for operational visibility
- Create and maintain runbooks for common operational issues
- Support developers with deployment and infrastructure questions
- Respond to and resolve infrastructure incidents

### Goals
- Enable fast, reliable deployments
- Maintain high system availability and observability
- Reduce manual toil through automation

### Typical Communication
- CI/CD pipeline discussions and troubleshooting
- Infrastructure and deployment documentation
- Incident response and post-mortems

### Interaction with Other Roles
- Supports **Developers** and **Release Manager** during deployments
- Collaborates with **Security Liaison** on compliance and security scanning requirements
- Works with **Technical Lead / Architect** on infrastructure architecture
- Escalates critical infrastructure issues to **Project Manager**

---

## Security Liaison

### Role Summary
Security Liaisons advise on security requirements, run threat assessments, ensure security scans are integrated into CI, and coordinate incident response. They embed security into the development lifecycle.

### Responsibilities
- Advise on security requirements for features and systems
- Conduct or coordinate threat assessments and security reviews
- Ensure security scanning tools are integrated into CI/CD
- Review and validate security acceptance criteria
- Coordinate security incident response with Security on-call
- Track and escalate security-related risks and vulnerabilities

### Goals
- Ensure compliance and reduce security risk
- Embed security into development practices
- Enable rapid response to security incidents

### Typical Communication
- Security requirement discussions during planning
- Code review comments on security issues
- Security incident escalations and updates

### Interaction with Other Roles
- Works with **Developers** to address security-related tasks and code review feedback
- Collaborates with **DevOps / Platform Engineer** on CI security scanning and infrastructure hardening
- Advises **Technical Lead / Architect** on architectural security considerations
- Escalates critical security issues to **Project Manager** and stakeholders

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers conduct user research, define UX acceptance criteria, and produce design specifications. They ensure solutions are user-centered and reduce rework from late design changes.

### Responsibilities
- Conduct user research and usability testing
- Define UX acceptance criteria and design specifications
- Produce design prototypes and mockups
- Collaborate on design trade-offs and feasibility
- Validate designs against user needs and accessibility standards
- Provide design guidance during implementation

### Goals
- Ensure user-centered solutions that meet customer needs
- Reduce rework and late-stage design changes
- Maintain consistency and quality of user experience

### Typical Communication
- Design reviews and feedback sessions
- User research findings and insights
- Design specifications and accessibility guidance

### Interaction with Other Roles
- Works with **Product Manager** to understand user needs and prioritize features
- Collaborates with **Developers** to ensure designs are feasible and well-implemented
- Advises on accessibility requirements aligned with organizational standards

---

## Data Analyst / Insights

### Role Summary
Data Analysts define success metrics, produce dashboards and analysis, and support experimentation. They enable data-driven decision-making and measure feature impact.

### Responsibilities
- Define success metrics aligned with project goals
- Produce dashboards and reporting for key signals
- Analyze feature usage and impact data
- Support A/B testing and experimentation
- Provide data-driven insights to inform prioritization
- Track and communicate results against success metrics

### Goals
- Enable data-driven decision-making
- Measure and communicate feature impact
- Support continuous improvement through insights

### Typical Communication
- Metric definitions and dashboard creation
- Analysis reports and insights summaries
- Weekly dashboards and KPI updates

### Interaction with Other Roles
- Works with **Product Manager** and **Project Manager** to define success metrics and inform prioritization
- Provides insights to **Developers** on feature usage and technical performance
- Collaborates on post-release analysis and retrospectives

---

## Support / Customer Success Representative

### Role Summary
Support and Customer Success Representatives surface customer-reported issues, validate post-release customer impact, and provide input on prioritization. They bridge customers and product teams.

### Responsibilities
- Surface customer-reported issues and feature requests
- Validate post-release customer impact and adoption
- Provide input on feature prioritization from customer perspective
- Support incident communication and customer outreach during incidents
- Gather customer feedback for product improvement
- Escalate critical customer issues to product and engineering teams

### Goals
- Ensure customer voice is heard in prioritization
- Minimize customer-facing impact from releases
- Enable rapid response to customer issues

### Typical Communication
- Customer feedback summaries and trend reports
- Post-release impact and adoption updates
- Incident communication and customer outreach

### Interaction with Other Roles
- Works with **Product Manager** to feed customer insights into prioritization
- Collaborates with **Developers** and **Project Manager** during incident triage and issue investigation
- Supports **Release Manager** with customer communication during releases
- Provides input to **Data Analyst** on customer metrics and satisfaction

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific personas in project checklists and workflows (e.g., Security Liaison in pre-release requirements, Release Manager in deployment checklist).
