# Code Reviews

## Overview

Code reviews are when developers check each other’s code before it gets added to the main branch. It’s basically a way of making sure the code is correct and follows the same standards across the team.

## Why It Matters

Code reviews are important because they help catch bugs early before the code goes live. They also improve the overall quality of the code and make it easier to understand. Another benefit is that team members can learn from each other by seeing different ways of solving problems.

They also act as an important quality control step before code is merged, helping reduce defects reaching production.

This also supports long-term maintainability of the codebase.

## Best Practices

- Keep pull requests small so they are easier to review  
- Review code within a reasonable time  
- Focus on logic, bugs and readability  
- Clearly explain what the changes are doing  
- Give feedback in a respectful and helpful way  
- Ensure pull requests include enough context for reviewers

## Bad Practices to Avoid

- Creating very large pull requests that are hard to review  
- Ignoring feedback from other developers  
- Merging code without it being properly reviewed  
- Only focusing on small things like formatting  
- Leaving reviews too late  

## Pull Request Workflow

In this team, code reviews will be done using pull requests. A developer creates a branch, makes their changes, and then opens a pull request. Another team member reviews the code and either suggests changes or approves it. Once approved, the code is merged into the main branch.

Pull requests should include a clear description of changes so reviewers can understand the context quickly.

## Common Challenges

Code reviews can become less effective when pull requests are too large or unclear. If there is too much going on in one pull request, it becomes harder for the reviewer to properly understand the changes and spot problems.

Another issue is delayed reviews. If a pull request sits waiting for too long, it slows down progress and makes the feedback less useful.

Teams can also spend too much time focusing on small formatting issues instead of more important things like logic, design and maintainability.

## Example

A developer submits a large pull request with many changes. The reviewer struggles to understand the logic and misses a bug during review. The issue is only discovered later in testing.

This shows why smaller pull requests and clear descriptions are important for effective code reviews.

## Further Reading

1. https://google.github.io/eng-practices/review/
2. https://www.atlassian.com/agile/software-development/code-reviews
3. https://martinfowler.com/articles/codeReview.html
4. https://abseil.io/resources/swe-book/html/ch09.html
5. https://solmaz.io/google-eng-practices-github

## Notes

- Code reviews help catch defects early
- Smaller pull requests are easier to review
- Reviews should focus on logic, not just formatting
- Feedback should be clear and constructive
- Code reviews also help with knowledge sharing across the team