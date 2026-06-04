# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **With Product Managers**: Clarify requirements, negotiate trade-offs, estimate effort
- **With Project Managers**: Provide status updates, flag blockers and dependencies
- **With QA/Testing**: Collaborate on acceptance criteria, respond to test findings
- **With UX Designer**: Review design specs, provide technical feasibility input
- **With Security Lead**: Address security feedback, implement security checks

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Managers**: Align on roadmap, priorities, and timeline
- **With Developers**: Refine requirements, negotiate scope and effort
- **With UX Designer**: Collaborate on user research, feature prioritization, design validation
- **With Data Analyst**: Review success metrics, prioritize features based on data
- **With Support Lead**: Incorporate user feedback and support trends into roadmap

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Managers**: Align on priorities and timeline
- **With Developers**: Manage schedule, track progress, remove blockers
- **With QA/Testing**: Coordinate testing cycles, manage quality gates
- **With Security Lead**: Track security reviews, manage security-related risks
- **With Support Lead**: Incorporate support escalations and user feedback into planning

---

## Extended Cross-Functional Roles

### UX Designer

#### Role Summary
UX Designers ensure that features and products are usable, intuitive, and aligned with user needs. They collaborate with Product Managers on requirements and work closely with Developers during implementation to translate design into code.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user acceptance criteria related to usability and design
- Review developer implementations against design specs
- Participate in design and code reviews
- Advocate for user needs and usability best practices

#### Goals
- Deliver user-centric, accessible, and intuitive interfaces
- Reduce design-to-implementation gaps
- Increase user satisfaction and adoption

#### Typical Communication
- Design kickoff meetings and design reviews
- Usability testing sessions and user feedback synthesis
- Design specifications and component libraries
- Code review comments on implementation fidelity

#### Key Interactions
- **With Product Managers**: Conduct user research, validate design direction, align on user needs
- **With Developers**: Provide design specs, review implementations, iterate on design details
- **With QA/Testing**: Define usability acceptance criteria, participate in UAT
- **With Technical Writer**: Ensure documentation reflects UI/UX accurately
- **With Support Lead**: Incorporate user feedback from support tickets into design improvements

---

### Technical Writer

#### Role Summary
Technical Writers own software and product documentation, creating guides, tutorials, API documentation, and release notes. They collaborate with Developers, Product Managers, and QA to ensure documentation is accurate, clear, and kept in sync with releases.

#### Responsibilities
- Create and maintain user guides, tutorials, and API documentation
- Draft release notes and migration guides
- Collaborate with developers to understand features and technical details
- Conduct documentation reviews and style consistency checks
- Incorporate feedback from QA and Support teams
- Maintain documentation versioning aligned with product releases

#### Goals
- Provide clear, accessible documentation for users and developers
- Reduce support escalations through better documentation
- Maintain documentation quality and consistency across all channels

#### Typical Communication
- Documentation reviews and feedback sessions
- Feature specification kickoffs (to understand what to document)
- Collaboration with QA on test scenarios and acceptance criteria
- Regular syncs with Support to understand documentation gaps

#### Key Interactions
- **With Product Managers**: Understand feature goals and user personas
- **With Developers**: Get technical details, review code for documentation needs, clarify complex logic
- **With QA/Testing**: Validate documentation accuracy, identify undocumented features
- **With UX Designer**: Ensure UI terminology matches documentation, align on terminology
- **With Support Lead**: Identify documentation gaps from support tickets, create guides for common issues

---

### Security Lead

#### Role Summary
Security Leads coordinate security activities throughout the project lifecycle, including threat modeling, security reviews, and incident response. They work with Developers and QA to integrate security checks into the CI/CD pipeline and ensure the team follows security best practices.

#### Responsibilities
- Conduct threat modeling and security architecture reviews
- Define and maintain security standards and policies
- Review code and designs for security vulnerabilities
- Integrate security scanning into CI/CD pipeline
- Respond to and triage security incidents
- Provide security training and guidance to the team
- Track security compliance and audit requirements

#### Goals
- Reduce security vulnerabilities and risks in production
- Maintain secure development practices across the team
- Ensure compliance with security regulations and standards

#### Typical Communication
- Security review meetings and threat modeling sessions
- Security incident response communications
- Security scanning results and remediation guidance
- Security training and best practices documentation

#### Key Interactions
- **With Developers**: Review code for security issues, provide remediation guidance, conduct security training
- **With Project Managers**: Flag security risks, manage remediation timelines
- **With QA/Testing**: Define security test cases, validate security fixes
- **With Product Managers**: Influence security requirements and prioritization
- **With Support Lead**: Triage security-related support escalations

---

### Data Analyst

#### Role Summary
Data Analysts gather, interpret, and communicate metrics for both product and delivery. They partner with Product Managers to measure success criteria and guide feature prioritization with quantitative insights, and with Project Managers to track delivery metrics and team velocity.

#### Responsibilities
- Define and track success metrics and KPIs
- Conduct data analysis and create dashboards
- Generate reports and insights for decision-making
- Collaborate on experiment design and A/B testing
- Monitor product usage and user behavior
- Support incident investigation with data
- Track delivery metrics (velocity, cycle time, burndown)

#### Goals
- Provide data-driven insights to guide product and delivery decisions
- Identify trends and opportunities for optimization
- Enable the team to measure and improve outcomes

#### Typical Communication
- Weekly metric reviews and dashboard updates
- Data analysis reports and insights presentations
- Experiment design and results communications
- Collaboration on success criteria and KPI definitions

#### Key Interactions
- **With Product Managers**: Define success metrics, analyze feature impact, guide prioritization
- **With Project Managers**: Track delivery metrics, identify trends, support process improvements
- **With Developers**: Explain metric definitions, provide performance insights
- **With Support Lead**: Analyze support metrics, identify product quality issues
- **With QA/Testing**: Correlate quality metrics with test coverage

---

### Support Lead

#### Role Summary
Support Leads serve as the liaison between users and the engineering team. They triage escalated bugs and issues from the field, work with QA to verify fixes, and keep Product and Project Managers informed of trends in support tickets and user feedback.

#### Responsibilities
- Manage support ticket queue and escalations
- Triage bugs and feature requests from users
- Collaborate with QA to verify issue reproduction and fixes
- Synthesize support feedback and identify trends
- Communicate user pain points and feature requests to Product Managers
- Participate in incident response for critical issues
- Maintain support documentation and runbooks

#### Goals
- Resolve user issues quickly and effectively
- Identify and escalate critical product quality issues
- Transform user feedback into product improvements

#### Typical Communication
- Support ticket reviews and triage meetings
- Bug reports and reproduction steps
- Incident communication and status updates
- Regular syncs with Product and Project Managers on trends
- Feedback synthesis and feature request prioritization

#### Key Interactions
- **With Developers**: Report bugs with reproduction steps, verify fixes
- **With QA/Testing**: Work together to reproduce issues, validate fixes
- **With Product Managers**: Report trends, escalate user feedback, suggest feature ideas
- **With Project Managers**: Inform of critical issues, support timeline planning
- **With Data Analyst**: Analyze support metrics, identify quality trends

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Key Interactions" section to understand cross-functional collaboration points and communication patterns.
