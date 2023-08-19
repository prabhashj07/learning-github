# Git Hooks

Git hooks are scripts that Git executes before or after certain events, such as committing, merging, and pushing. They enable you to automate actions and enforce standards. Here's how to use Git hooks:

## Types of Hooks

- **Pre-commit**: Run before committing changes. Useful for enforcing coding standards or running tests.
- **Pre-push**: Run before pushing changes. Useful for running tests or checks before code is shared.
- **Post-commit, post-merge, post-checkout**: Run after corresponding events.

## Setting Up Hooks

1. In your repository, navigate to the `.git/hooks` directory.
2. Rename the desired hook template (e.g., `pre-commit.sample`) to remove `.sample` extension.
3. Create or edit the script in the hook file.

Hooks are a powerful tool for maintaining code quality and enforcing best practices throughout your team.
