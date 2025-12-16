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

## Product Owner

### Role Summary
Product Owners define and communicate the product vision, prioritize the backlog to maximize value, and serve as the primary point of contact between stakeholders and the delivery team. They ensure the team builds the right things in the right order.

### Responsibilities
- Define and communicate the product vision and strategy
- Maintain and prioritize the product backlog based on business value
- Write clear user stories with acceptance criteria
- Make timely decisions on scope and trade-offs
- Accept or reject completed work based on acceptance criteria
- Collaborate with stakeholders to gather feedback and requirements

### Goals
- Maximize return on investment (ROI) and business value
- Ensure the product backlog is transparent, visible, and understood
- Maintain stakeholder confidence through regular communication
- Balance competing priorities effectively

### Typical Communication
- Backlog refinement sessions with the team
- Sprint planning and reviews
- Stakeholder demonstrations and feedback sessions
- Regular one-on-ones with Product Managers and Project Managers

### Collaboration Example
The Product Owner works closely with the **Product Manager** to align the product backlog with the broader product strategy and roadmap. During sprint planning, they collaborate with **Developers** to clarify user stories and acceptance criteria, ensuring the team understands the "why" behind each item. They partner with the **Scrum Master** to facilitate backlog refinement and with the **Quality Advocate** to define testable acceptance criteria. When conflicts arise between stakeholder requests, the Product Owner consults with the **Project Manager** to understand resource constraints and delivery timelines before making prioritization decisions.

---

## Release Manager

### Role Summary
Release Managers plan and coordinate software releases, manage deployment schedules, and ensure smooth transitions from development to production. They serve as the central point of coordination for all release activities.

### Responsibilities
- Plan release schedules and coordinate deployment windows
- Manage release artifacts and version control
- Coordinate go/no-go decisions with stakeholders
- Communicate release status, timelines, and risks
- Maintain release documentation and runbooks
- Coordinate rollback procedures when necessary

### Goals
- Ensure reliable, predictable release cadence
- Minimize deployment risks and downtime
- Maintain clear communication across all teams
- Continuously improve release processes

### Typical Communication
- Release planning meetings with engineering and operations
- Go/no-go checkpoint meetings before deployments
- Release notes and deployment announcements
- Post-release status reports to stakeholders

### Collaboration Example
The Release Manager coordinates with **Developers** to understand which features are ready for release and any technical dependencies. They work with the **Project Manager** to align release timelines with project milestones and communicate any schedule impacts. During release planning, they collaborate with the **Quality Advocate** to ensure all testing gates have been met and with **Product Managers** to confirm feature readiness and customer communication plans. If issues arise during deployment, they coordinate with the **Scrum Master** to quickly triage and decide on rollback or hotfix strategies.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather requirements, document user stories, analyze data, and ensure that technical teams understand stakeholder needs and business context.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into clear, actionable user stories
- Conduct process analysis and identify improvement opportunities
- Create functional specifications and workflow diagrams
- Facilitate requirements workshops and validation sessions
- Analyze data to support decision-making

### Goals
- Ensure technical solutions address actual business needs
- Reduce ambiguity and rework through clear documentation
- Improve communication between business and technical teams
- Support data-driven decision-making

### Typical Communication
- Requirements gathering sessions with stakeholders
- Workshops to validate and refine specifications
- Documentation reviews with developers and QA
- Data analysis presentations to leadership

### Collaboration Example
The Business Analyst works with **Product Managers** and **Product Owners** to understand the business vision and translate it into detailed requirements. They conduct workshops with stakeholders to gather needs, then partner with **Developers** to ensure technical feasibility and clarity of acceptance criteria. During implementation, they collaborate with the **Quality Advocate** to define test scenarios that validate business rules. The Business Analyst also supports the **Project Manager** by providing impact analysis and effort estimates for proposed changes, helping inform prioritization decisions.

---

## Scrum Master / Project Facilitator

### Role Summary
Scrum Masters (or Project Facilitators in non-Scrum contexts) serve the team by facilitating Agile ceremonies, removing impediments, and fostering continuous improvement. They enable the team to work at their highest potential.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments that slow the team
- Coach the team on Agile principles and practices
- Shield the team from external distractions
- Track and visualize team metrics (velocity, burndown, cycle time)
- Drive continuous improvement through retrospective actions

### Goals
- Maximize team productivity and focus
- Foster a culture of transparency and continuous learning
- Ensure Agile ceremonies are effective and time-boxed
- Help the team become self-organizing

### Typical Communication
- Daily standups and ceremony facilitation
- One-on-ones with team members to address concerns
- Impediment escalation to Project Managers or leadership
- Team health and velocity reports

### Collaboration Example
The Scrum Master facilitates ceremonies where the **Product Owner** presents and prioritizes backlog items, ensuring the team understands priorities and acceptance criteria. They work closely with **Developers** to identify and remove impediments—whether technical blockers, dependency issues, or process inefficiencies. When systemic issues arise, they escalate to the **Project Manager** for cross-team coordination. The Scrum Master partners with the **Quality Advocate** to ensure quality practices are integrated into the team's workflow and collaborates with the **Release Manager** to align sprint commitments with release schedules.

---

## Quality Advocate

### Role Summary
Quality Advocates champion quality throughout the development lifecycle. They define test strategies, ensure acceptance criteria are testable, and promote quality practices across the team—not just at the end of development.

### Responsibilities
- Define test strategies and approaches for features and releases
- Ensure acceptance criteria are clear, complete, and testable
- Advocate for automated testing and quality gates in CI/CD
- Perform exploratory testing and validate edge cases
- Track and report on quality metrics (defect trends, coverage)
- Coach developers on testing best practices

### Goals
- Prevent defects through early quality practices
- Ensure deliverables meet acceptance criteria before release
- Build a culture of shared quality ownership
- Increase test automation coverage

### Typical Communication
- Test planning sessions during sprint planning
- Bug triage meetings with developers and product owners
- Quality metrics dashboards and reports
- Retrospectives to discuss quality improvements

### Collaboration Example
The Quality Advocate works with the **Product Owner** and **Business Analyst** during backlog refinement to ensure user stories include testable acceptance criteria. They partner with **Developers** to review test plans, promote test-driven development, and conduct code reviews focused on testability. Before releases, they collaborate with the **Release Manager** to confirm all quality gates have been met and provide go/no-go recommendations. The Quality Advocate also works with the **Scrum Master** to identify quality process improvements and track metrics that inform retrospective discussions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of personas helps clarify role boundaries, reduce ambiguity, and support effective onboarding by illustrating how different roles collaborate throughout the project lifecycle.

