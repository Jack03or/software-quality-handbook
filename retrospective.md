# Retrospective

## Overview

This retrospective looks back at how we built the Software Quality Handbook — what worked, what didn't, and what we'd do differently. We followed a GitHub workflow throughout, using feature branches, pull requests, and peer reviews, which kept things structured even when the work got messy.

---

## What Went Well

The pull request workflow was probably the most useful thing we did. Every change went through a branch, got reviewed, and was only merged once someone approved it. It slowed things down slightly but caught issues we would have missed otherwise.

Feedback actually got applied. When someone left a comment on a pull request, the author updated the content and pushed again. It became a habit fairly quickly and the sections genuinely improved because of it.

Communication was straightforward. We used WhatsApp for quick coordination and it worked fine. No missed messages, no confusion about who was doing what.

The diagrams were a good call. Each person made a diagram for someone else's section, which meant everyone had to understand all three topics, not just their own. It also made the handbook look a lot more polished.

---

## Challenges Faced

Git caused a headache at one point. A pull request got stuck because local changes conflicted with the remote version. It meant discarding local work and pulling the latest before continuing. Not a disaster, but a reminder to pull before starting work on a branch.

Formatting was inconsistent early on. The Further Reading sections looked different across files and had to be tidied up later. It was a small thing but added unnecessary work.

One pull request looked much larger than it was because the code editor auto-formatted the file on save. The content hadn't actually changed but the diff was huge, which made reviewing it harder than it needed to be.

---

## What We Learned

Pull requests and code reviews make more sense in practice than in theory. Reading about them is one thing — actually doing them, leaving feedback, and watching the content improve because of it is different.

Finding good sources took longer than expected. The brief asked for resources based on real experience rather than theory, which meant ruling out a lot of the obvious results and digging further.

Trunk based development felt confusing at first but clicked quickly. Short branches, frequent merges, no long running feature work sitting around waiting to cause conflicts.

---

## What We Would Do Differently

Apply feedback within the same pull request rather than opening a new one for each small change. It would keep the history cleaner and reduce unnecessary back and forth.

Set formatting rules at the start. Fixing inconsistencies later is annoying and avoidable.

---

## Development Approach

We used short lived feature branches and merged frequently into main through pull requests. Each PR needed at least one approval before merging. This kept the main branch stable and meant nobody was working on stale code for long.

![Trunk Based Development](images/TrunkBasedDiagramSqa.png)

*Figure: Our team's trunk based development workflow, showing how we managed feature branches and pull requests throughout the project.*

---

## Team Contributions

- Jack focused on Task Estimation, contributed to Code Reviews, created the Defect Management diagram, and developed the README.
- Dylan focused on Code Reviews, contributed to Defect Management, and created the Task Estimation diagram.
- Shane focused on Defect Management, contributed to Task Estimation, and created the Code Reviews diagram.

All three reviewed each other's pull requests throughout the project.