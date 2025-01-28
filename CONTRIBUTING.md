# Contributing Best Practices @ Aiera

## Pull Request Guidelines

1. **Create Small, Focused PRs**
   - Aim to create small, focused pull requests that fulfill a single purpose
   - Smaller pull requests are easier and faster to review and merge
   - Leave less room to introduce bugs and provide a clearer history of changes
   - If a large change is needed, consider breaking it into smaller, logical PRs

2. **Self-Review Process**
   - Review, build, and test your own pull request before submitting it
   - Run all relevant tests locally
   - Check for code style consistency
   - Ensure commit messages are clear and follow our conventions
   - Review your own diff to catch unintended changes

3. **Clear Documentation**
   - Write clear titles and descriptions that help reviewers understand the PR's purpose
   - For multi-file changes, provide a suggested review order
   - Include any relevant context or background information
   - Link to related issues or dependent PRs

4. **Testing Requirements**
   - Add or update tests for new functionality
   - Ensure all existing tests pass
   - Include test coverage for bug fixes to prevent regressions
   - Document any manual testing steps if applicable

5. **Code Quality Standards**
   - Follow our code style guidelines and conventions
   - Include appropriate documentation and comments
   - Remove debug code, commented-out code, and console logs 
   - Ensure proper error handling
   - Keep code modular and reusable where appropriate

6. **Branch Management**
   - Create branches from the latest main/develop branch
   - Keep branches up to date with their base branch
   - Delete branches after merging
   - Use meaningful branch names following our naming convention (via Monday GitHub integration

7. **Review Process**
   - Respond to review comments promptly
   - Tag appropriate reviewers
   - Use the suggestion feature for small changes
   - Mark conversations as resolved when addressed
   - Request re-review when making significant changes

8. **Deployment Considerations**
   - Include any necessary database migrations
   - Document configuration changes
   - Consider backward compatibility
   - Note any deployment dependencies or special instructions

## PR Template Guide

When creating a pull request, please include:

1. **What**
   - Clear description of the changes
   - Why these changes are necessary
   - Any alternative approaches considered

2. **How to Test**
   - Step-by-step testing instructions
   - Required environment setup
   - Expected outcomes

3. **Screenshots/Videos/Diagrams**
   - Include visual evidence of changes when applicable
   - Before/after comparisons for UI changes

4. **Technical Notes**
   - Architecture decisions
   - Performance implications
   - Security considerations
   - Known limitations or technical debt

**Your future self thanks you for all these notes.**

## Best Practices for Commits

1. Write meaningful commit messages
2. Keep commits atomic and focused

**Good Commit**: `Refactor error handling method for ASR to better handle new edge case`

**Bad Commit**: `ongoing`

## Getting Help

- Tag specific team members for domain-specific questions
- Use team channels for broader discussions
- Reference documentation
- Ask for clarification when review comments are unclear

Remember: The goal is to maintain high code quality while making the review process efficient and effective for everyone involved.
