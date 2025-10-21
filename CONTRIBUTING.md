# Contributing

First: thank you for your interest in contributing — we appreciate your time and effort.

This document explains how to report issues, propose features, and contribute code, documentation, or other improvements.

## Table of Contents
- Code of Conduct
- Ways to Contribute
- Reporting Bugs
- Suggesting Enhancements
- Development Setup
- Branching & Commits
- Pull Request Process
- Tests & CI
- Style & Linting
- PR Checklist
- Where to get help

## Code of Conduct
This project follows the Code of Conduct in CODE_OF_CONDUCT.md. By participating, you agree to abide by its terms.

## Ways to Contribute
- Report bugs and include steps to reproduce
- Propose features or improvements
- Improve documentation or examples
- Submit bug fixes and enhancements via pull requests
- Review and test open PRs

## Reporting Bugs
When filing a bug report, please include:
- A clear and descriptive title
- Steps to reproduce
- Expected and actual behavior
- Environment details (OS, versions)
- Minimal reproducible example or link to a small repo

Use the issue template (if present) to capture this information.

## Suggesting Enhancements
When suggesting a feature:
- Explain the problem you want to solve
- Describe the desired behavior and alternatives considered
- Provide examples of usage and potential API changes

## Development Setup
General steps (adjust commands for your project language/tooling):
1. Fork the repository and clone your fork:
   - git clone git@github.com:your-username/your-fork.git
2. Add upstream remote and fetch:
   - git remote add upstream git@github.com:owner/repo.git
   - git fetch upstream
3. Create a feature branch:
   - git checkout -b feat/my-feature
4. Install dependencies and run the project/tests:
   - Follow the README for language-specific instructions (e.g., npm install, pip install -r requirements.txt)

If you want, paste your project's README or tell me the language and I’ll add exact commands here.

## Branching & Commit Messages
- Use branches for each change: feat/..., fix/..., docs/...
- Keep branches small and focused
- Commit message format (recommended):
  - Short imperative summary (<=50 chars)
  - Blank line
  - More detailed description if needed
- Example:
  - feat(parser): add support for X

Consider enabling signed commits or DCO if required by your project.

## Pull Request Process
1. Fork & branch from latest main (or the project's default branch)
2. Make changes, run tests and linters locally
3. Push your branch to your fork
4. Open a PR against the project's default branch with:
   - Clear title
   - Description of the change and rationale
   - Any relevant screenshots, logs, or sample usage
   - Reference related issues with Fixes #NN where applicable
5. Respond to review comments and update the PR

Be patient and cooperative during review; maintainers may request changes.

## Tests & Continuous Integration
- Add tests for any significant changes
- Run the test suite before opening PRs
- Ensure CI (if present) passes on your branch
- If you add new dependencies, explain why and how they’re used

If you tell me your test command (e.g., npm test, pytest), I can add exact instructions.

## Style & Linting
- Follow the existing code style
- Use provided linters and formatters (e.g., Prettier, ESLint, Black)
- Run linters locally and fix warnings before submitting

## PR Checklist
- [ ] I have read the Code of Conduct
- [ ] My code follows the project style
- [ ] I added or updated tests where applicable
- [ ] I updated documentation if necessary
- [ ] All CI checks pass
- [ ] I have rebased/synced with the latest default branch

## Where to get help
If you have questions, open an issue or contact the maintainers via the project’s preferred channel (replace with your chat/email). For faster help, include reproduction steps and the output of any failing tests.
