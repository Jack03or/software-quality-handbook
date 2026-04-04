# Defect Management

## Overview

Defect management is the process of identifying, tracking, prioritising and resolving defects in a software project.
A structured defect management process ensures that issues are handled consistently and efficiently. Without this, defects can be missed or resolved in the wrong order.

### Defect Lifecycle Diagram

![Defect Lifecycle Diagram](../images/DefectLifecycleChart.png)

_Figure: Example defect lifecycle showing how issues move from reporting to closure._

## Why It Matters

- Helps teams decide which defects to fix first when time and resources are limited
- Ensures high-impact issues affecting core functionality or users are prioritised
- Prevents less important bugs from blocking releases or important milestones
- Keeps the team aligned on what is considered critical versus minor issues

## Best Practices

- Record defects clearly
- Include steps to reproduce the issue
- Agree on severity and priority levels
- Track defects through a defined lifecycle
- Fix high-priority issues first
- Use a tracking tool to manage and monitor defects
- Prioritise defects based on business impact rather than treating all issues equally

## Example

A tester logs a defect with the description "button not working" and no steps to reproduce. The developer cannot replicate the issue and marks it as closed. The same bug is reported again two weeks later by a different tester. This time it is investigated properly and turns out the button fails only when a user has a specific account type. By this point the feature has already been released to some users.

The original report should have included clear steps to reproduce the issue, the conditions it occurs under, and the expected versus actual behaviour. A structured defect process with proper lifecycle tracking would have prevented the issue from being closed prematurely and caught it before release.

## Common Challenges

- Incomplete defect reports slow everything down. Without steps to reproduce, screenshots, or environment details, developers waste hours trying to replicate the issue rather than fixing it.
- Mixing up severity and priority leads to the wrong bugs getting fixed first. Severity is about how broken the code is, priority is about how much it matters to users. Get them confused and you end up with cosmetic issues blocking releases while data bugs sit untouched.
- Poor communication between testers and developers leaves defects stuck in limbo. One side thinks it is fixed, the other does not, and nobody updates the status during handoffs.
- Without clear ownership or regular triage, high impact bugs can sit unassigned for days while the team works through lower priority problems. By the time someone picks them up the damage is already done.
- Skipping lifecycle stages like assigned, fixed, and retest means defects fall through the cracks. A bug marked as fixed is not the same as a bug that has been verified and closed.
- Logging every minor issue without filtering clutters the defect board fast. When everything is in there, nothing stands out and the real priorities get buried.

## Bad Practices to Avoid

- Reporting defects with little or no detail
- Confusing severity with priority
- Ignoring or delaying defect updates
- Fixing issues without properly tracking them
- Poor communication between team members
- Treating all defects as equally urgent regardless of their impact on the system

## Further Reading

- https://www.testrail.com/blog/defect-management/
- https://testsigma.com/blog/defects-in-software-testing/
- https://testrigor.com/blog/defect-based-testing/
- https://www.browserstack.com/guide/defect-management-in-software-testing
- https://katalon.com/resources-center/blog/defect-management-in-software-testing
- https://testomat.io/blog/bug-life-cycle-in-software-testing/
- https://www.alooba.com/skills/concepts/defect-management-423/defect-prioritization/
- https://www.caktusgroup.com/blog/2018/04/30/prioritizing-defects/

## Notes from Reading Sources

**TestRail: Defect Management:**

- Defect management is a structured process for identifying, tracking, prioritising, and resolving defects
- Clear defect reports should include steps to reproduce the issue and enough detail for the developer to understand the problem
- Defects should move through a proper lifecycle so nothing gets lost or forgotten
- Prioritising based on business impact helps teams focus on the most important issues first

**TestSigma: Defects in Software Testing:**

- A defect is not always the same as a failure, so teams need to be clear about what kind of issue they are dealing with
- Severity and priority are different, and mixing them up can lead to poor decisions
- Good defect tracking improves communication between testers and developers

**BrowserStack: Defect Management in Software Testing:**

- A good defect process helps teams avoid missed bugs and keeps the workflow organised
- Defects should be logged consistently so the team can monitor status and progress
- Tracking tools make it easier to manage and update defects properly

**Testomat: Bug Life Cycle in Software Testing:**

- Defects usually follow a lifecycle such as new, assigned, fixed, retested, and closed
- A clear lifecycle makes it easier for the team to know where each bug stands
- Without updates, defects can be delayed or forgotten

**Katalon: Defect Management in Software Testing:**

- Defect management prevents bugs from slipping into production by catching them early
- Teams should use consistent severity/priority matrices to avoid confusion about fix order
- Automated tools help track defects through their full lifecycle from logging to verification

**TestRigor: Defect-Based Testing:**

- Focus testing on likely defect areas rather than rigid test case coverage
- Good reports need environment details such as browser, OS, and version since bugs often appear in specific setups
- Retesting fixed defects is critical — fixed does not mean verified working

**Alooba: Defect Prioritization:**

- Prioritization balances business risk, frequency of occurrence, and fix cost
- High severity/low priority bugs such as rare crashes can wait if they do not affect many users
- Regular triage meetings keep the defect backlog manageable

**Caktus Group: Prioritizing Defects:**

- Severity describes how bad the bug is technically, while priority shows business urgency
- Use a matrix combining impact and likelihood to decide fix order, not just gut feel
- Fix critical path blockers first, even if they are small code changes
