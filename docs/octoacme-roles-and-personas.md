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

## QA / Testing

### Role Summary
QA professionals ensure product quality by validating features against acceptance criteria, finding defects, and verifying fixes. They collaborate with developers and product managers to establish quality standards and testing strategies.

### Responsibilities
- Design and execute test plans and test cases
- Validate features against acceptance criteria
- Report and track defects through resolution
- Participate in requirement reviews and provide testability feedback
- Maintain automated test suites where applicable
- Verify releases before deployment

### Goals
- Ensure product meets quality standards and user expectations
- Identify issues early in the development cycle
- Improve test coverage and automation
- Reduce production defects

### Typical Communication
- Participate in sprint planning and refinement
- Collaborate with developers on bug reports and fixes
- Provide QA sign-off before releases
- Share test results and quality metrics

---

## UX Designer

### Role Summary
UX Designers ensure user-centric design and usability across all product features. They translate user needs into intuitive interfaces and collaborate closely with product managers, developers, and QA to deliver exceptional user experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate user flows and interaction patterns
- Collaborate on acceptance criteria with Product Manager
- Provide design feedback during development and demos
- Ensure consistency with design system and brand guidelines
- Participate in user story refinement and planning

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across product features
- Validate designs through user feedback and metrics

### Typical Communication
- Design reviews with Product Manager and stakeholders
- Collaboration sessions with Developers on implementation
- Usability testing sessions and findings presentations
- Feedback during sprint demos and QA validation

---

## Release Manager

### Role Summary
Release Managers oversee release planning, deployment coordination, and incident response. They ensure smooth, reliable releases by orchestrating stakeholders, validating readiness, and maintaining release playbooks.

### Responsibilities
- Plan and schedule releases with Product and Project Managers
- Coordinate go/no-go decisions with stakeholders
- Maintain release checklists and deployment playbooks
- Oversee deployment execution and post-release validation
- Manage release communications to stakeholders
- Track release metrics and improve release processes
- Coordinate rollback procedures when needed

### Goals
- Deliver reliable, low-risk releases on schedule
- Minimize deployment-related incidents
- Maintain transparent release status and communications
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with PM and engineering leads
- Go/no-go reviews with stakeholders before deployment
- Release announcements and status updates
- Post-release retrospectives and incident reviews

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, cloud infrastructure, and observability systems. They collaborate with developers to enable rapid, reliable deployments and maintain production stability.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage cloud infrastructure and deployment environments
- Implement monitoring, logging, and alerting systems
- Support developers with build and deployment issues
- Automate testing and deployment processes
- Manage production stability and performance
- Develop and test rollback strategies and disaster recovery plans

### Goals
- Enable fast, safe deployments through automation
- Maintain high system availability and performance
- Reduce manual deployment effort and errors
- Improve observability and incident response time

### Typical Communication
- Collaborate with Developers on pipeline improvements
- Coordinate with Release Manager on deployment readiness
- Share infrastructure metrics and incident reports
- Participate in post-incident reviews and retrospectives

---

## Business Analyst

### Role Summary
Business Analysts clarify requirements with stakeholders, write detailed user stories, and support Product Managers with metrics and process mapping. They bridge business needs and technical implementation.

### Responsibilities
- Conduct stakeholder interviews and requirements gathering
- Document business processes and workflows
- Write detailed user stories with acceptance criteria
- Define and track business metrics and KPIs
- Support Product Manager with data analysis and reporting
- Validate solutions meet business requirements
- Facilitate requirements workshops and reviews

### Goals
- Ensure clear, complete requirements for development
- Align technical solutions with business objectives
- Provide data-driven insights for decision-making
- Improve stakeholder communication and alignment

### Typical Communication
- Stakeholder interviews and requirements sessions
- User story refinement with Product Manager and Developers
- Metrics reviews and business reporting
- Requirement validation sessions with QA

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, maintain team flow, and remove blockers. They coach the team on agile practices and help maintain focus on delivery commitments.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Remove impediments and blockers for the team
- Coach team members on agile practices and principles
- Maintain sprint boards and ensure process transparency
- Track velocity and team health metrics
- Protect team from external disruptions
- Foster continuous improvement through retrospectives

### Goals
- Maintain predictable, sustainable delivery rhythm
- Maximize team productivity and collaboration
- Reduce cycle time and improve flow
- Build high-performing, self-organizing teams

### Typical Communication
- Daily standups and sprint ceremonies facilitation
- One-on-ones to address team member concerns
- Escalate blockers to Project and Product Managers
- Share team metrics and improvement initiatives
- Coordinate with other Scrum Masters for cross-team dependencies

---

## Interaction Examples: How Roles Collaborate

These examples illustrate how the expanded set of personas work together to support project delivery, release, and continuous improvement:

### Feature Development Flow
1. **Product Manager** defines feature vision and success metrics
2. **Business Analyst** conducts stakeholder interviews and writes detailed user stories
3. **UX Designer** creates wireframes and design specifications, validates with Product Manager
4. **Developers** implement feature following design specs and acceptance criteria
5. **QA** validates against acceptance criteria and provides feedback to UX Designer on usability
6. **Scrum Master** facilitates ceremonies and removes blockers throughout the process

### Release Coordination
1. **Release Manager** schedules release and creates deployment checklist
2. **DevOps Engineer** prepares infrastructure and validates CI/CD pipeline readiness
3. **QA** performs final validation and signs off on release candidate
4. **Release Manager** conducts go/no-go review with Product Manager and stakeholders
5. **DevOps Engineer** executes deployment following release playbook
6. **Release Manager** coordinates post-deployment validation and stakeholder communications

### Requirements Refinement
1. **Business Analyst** gathers requirements from stakeholders and documents business processes
2. **Product Manager** prioritizes based on business value and strategic goals
3. **UX Designer** refines acceptance criteria with focus on user experience and usability
4. **Developers** provide technical feasibility input and effort estimates
5. **QA** reviews for testability and suggests test scenarios
6. **Scrum Master** facilitates the refinement session and ensures team alignment

### Continuous Improvement
1. **Scrum Master** facilitates retrospective and captures improvement actions
2. **Project Manager** incorporates actions into project plans and risk management
3. **DevOps Engineer** implements process automation improvements
4. **Release Manager** updates release playbooks based on lessons learned
5. **Business Analyst** tracks improvement metrics and reports on impact
6. **Product Manager** adjusts roadmap priorities based on team feedback and data

### Cross-functional Problem Solving
- **UX Designer** identifies usability issue through user testing
- **Business Analyst** quantifies business impact with metrics
- **Product Manager** prioritizes fix based on user impact and business value
- **Scrum Master** brings issue to sprint planning and facilitates discussion
- **Developers** propose technical solution
- **DevOps Engineer** ensures solution is monitorable and deployable
- **QA** defines validation criteria
- **Release Manager** plans deployment timing to minimize user disruption

These interaction patterns demonstrate clear ownership, communication paths, and accountability. They ensure the right people are involved at the right time, supporting effective onboarding, reduced ambiguity, and improved project outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction examples show how roles complement each other and can be used to model realistic project workflows.

