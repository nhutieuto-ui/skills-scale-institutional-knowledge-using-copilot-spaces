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

## Quality Assurance (QA) / Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and execution. They define testing approaches, establish quality standards, and validate that work meets acceptance criteria before release.

### Responsibilities
- Define test strategy and approach (unit, integration, e2e, performance)
- Create and maintain test plans aligned with backlog items
- Execute manual and automated testing
- Identify and document defects with clear reproduction steps
- Validate acceptance criteria are met before sign-off
- Partner with developers on test design and coverage
- Recommend quality improvements and process enhancements

### Goals
- Ensure release quality and customer satisfaction
- Reduce escaped defects and post-release issues
- Build testing practices that scale with the product

### Typical Communication
- Test planning sessions with developers and PMs
- Daily standups and sprint reviews
- Defect reports and quality metrics dashboards

### Interaction with Other Roles
- Works closely with **Developers** to define testable requirements and conduct joint reviews of acceptance criteria
- Collaborates with **Product Managers** to validate features against business requirements
- Partners with **Technical Leads** on test architecture and automation strategy
- Reports quality metrics and risks to **Project Managers** for escalation if needed
- Supports **Security Engineers** by including security test cases in the test plan

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, ensure architectural alignment, and help teams navigate technical complexity and risk.

### Responsibilities
- Review and approve technical designs before implementation
- Identify architectural risks and propose mitigations
- Mentor developers and support technical problem-solving
- Ensure code quality and adherence to technical standards
- Manage technical debt and refactoring priorities
- Collaborate with cross-team technical dependencies
- Assist in capacity planning and technical estimation

### Goals
- Build sustainable, maintainable systems
- Minimize technical risk and rework
- Support team learning and capability growth

### Typical Communication
- Design review sessions
- Technical spike planning and guidance
- Code review feedback and mentorship

### Interaction with Other Roles
- Guides **Developers** on architecture, design patterns, and best practices
- Works with **Product Managers** to understand requirements and propose technical approaches
- Partners with **QA/Testing Leads** on test architecture and automation frameworks
- Collaborates with **DevOps Engineers** on deployment and infrastructure considerations
- Consults with **Security Engineers** on threat modeling and secure design principles
- Reports technical risks to **Project Managers** during planning and execution phases

---

## Stakeholder / Business Owner

### Role Summary
Stakeholders and Business Owners represent organizational priorities and business value. They provide approval authority, establish success metrics, and ensure alignment between project outcomes and business goals.

### Responsibilities
- Define business objectives and success criteria for the project
- Approve project charter and major decisions
- Provide organizational context and constraints
- Review and validate completed work aligns with business needs
- Communicate project status and outcomes to leadership
- Balance scope, budget, and timeline trade-offs

### Goals
- Maximize return on investment
- Ensure business value delivery
- Align project outcomes with organizational strategy

### Typical Communication
- Project kickoff and approval meetings
- Monthly stakeholder updates and reviews
- Sign-off on major milestones and releases
- Decision logs and business case documentation

### Interaction with Other Roles
- Partners with **Project Managers** for regular status updates and decision-making
- Works with **Product Managers** to ensure features align with business strategy
- Reviews deliverables with **Developers** and **QA Leads** during acceptance reviews
- Escalates constraints and organizational changes to **Project Managers**

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers manage deployment pipelines, infrastructure provisioning, and operational readiness. They ensure systems are reliable, scalable, and secure in production.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Provision and manage infrastructure (cloud, on-premise, hybrid)
- Implement monitoring, logging, and alerting systems
- Manage secrets, credentials, and access controls
- Support incident response and postmortems
- Document runbooks and operational procedures
- Collaborate on performance optimization and capacity planning

### Goals
- Enable fast, reliable deployments with minimal downtime
- Maintain high system availability and performance
- Support team velocity through automation and self-service tools

### Typical Communication
- Infrastructure planning and design reviews
- Deployment windows and release coordination
- Incident reports and postmortem documentation
- Infrastructure-as-code reviews

### Interaction with Other Roles
- Works with **Developers** to enable CI/CD practices and provide deployment tooling
- Collaborates with **Technical Leads** on architecture and infrastructure patterns
- Partners with **QA Leads** on staging environment setup and test infrastructure
- Coordinates with **Project Managers** on release schedules and deployment windows
- Supports **Security Engineers** on compliance, data protection, and vulnerability patching

---

## Security Engineer

### Role Summary
Security Engineers ensure security requirements are met throughout the project lifecycle. They conduct risk assessments, review designs for security implications, and establish security practices.

### Responsibilities
- Conduct threat modeling and security assessments
- Review technical designs and code for security vulnerabilities
- Define security requirements and acceptance criteria
- Implement security testing and scanning in the CI/CD pipeline
- Manage vulnerability reporting and remediation
- Ensure compliance with security policies and standards
- Support incident response for security-related issues

### Goals
- Prevent security breaches and data loss
- Build security into the development process
- Maintain compliance with industry standards and regulations

### Typical Communication
- Security reviews during design phase
- Code and design review feedback
- Vulnerability reports and remediation plans
- Security metrics and compliance dashboards

### Interaction with Other Roles
- Partners with **Developers** to review code changes and provide secure coding guidance
- Collaborates with **Technical Leads** on threat modeling and secure architecture
- Works with **QA Leads** to include security test cases in the test plan
- Coordinates with **DevOps Engineers** on infrastructure security and compliance
- Reports security risks and findings to **Project Managers** for escalation
- Aligns security requirements with **Product Managers** for feature acceptance

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile practices, remove impediments, and coach teams on iterative delivery. They enable teams to work efficiently and continuously improve.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Help teams identify and remove impediments
- Coach team members on agile practices and mindset
- Maintain and optimize sprint cadence and team velocity
- Track and communicate team health and metrics
- Help resolve conflicts and improve collaboration
- Advocate for sustainable pace and continuous improvement

### Goals
- Enable high-performing, self-organizing teams
- Maximize team velocity and predictability
- Foster continuous learning and improvement culture

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching conversations
- Team retrospectives and action item tracking
- Velocity and team health reports

### Interaction with Other Roles
- Supports **Developers** by removing blockers and enabling focus time
- Collaborates with **Product Managers** on backlog refinement and sprint planning
- Partners with **Project Managers** on schedule and risk communication
- Coaches all team members on agile best practices
- Helps **Technical Leads** facilitate technical decision-making
- Supports retrospectives and action item follow-up across all roles

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the interaction sections to understand how personas collaborate across the project lifecycle.
