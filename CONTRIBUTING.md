# Contributing to checkup

Thank you for your interest in contributing to checkup — and welcome to Hacktoberfest! This document explains how to contribute, what makes a good contribution during Hacktoberfest, and how maintainers will review and accept contributions.

Table of contents
- Getting started
- Finding issues to work on
- Setup and running the project locally
- Code style & tests
- Making changes and commits
- Submitting a pull request
- Hacktoberfest guidance
- Code of Conduct
- License & Contact

---

## Getting started

1. Fork the repository to your GitHub account.
2. Clone your fork:
```bash
git clone https://github.com/<your-username>/checkup.git
```
3. Create a descriptive branch:
```bash
git checkout -b feat/short-description
# or for fixes
git checkout -b fix/short-description
```

---

## Finding issues to work on

- Look for issues labeled `good first issue`, `help wanted`, or `hacktoberfest`.
- If you can’t find an existing issue that matches your idea, open an issue describing the change and start a discussion before coding.
- For Hacktoberfest, prefer issues labeled `good first issue` or `hacktoberfest`. Maintainers may also mark merged or accepted PRs with the label `hacktoberfest-accepted` so they count for the event.

---

## Setup and running the project locally

This repo may use different languages or runtimes. The commands below are typical for a Node.js project; if this repository uses another language, substitute the appropriate commands (for example, Python, Go, Rust, etc.).

- Requirements: Node.js >= 14 and npm or yarn (or the project's language/runtime).
- Install dependencies:
```bash
npm install
# or
yarn
```
- Run the test suite:
```bash
npm test
```
- Run linters/formatters if available:
```bash
npm run lint
npm run format
```

If the repository uses a different runtime, please check the README for language-specific setup steps or open an issue if the setup is unclear.

---

## Code style & tests

- Follow the existing code style and patterns in the repository.
- Use the project's formatters and linters (Prettier, ESLint, gofmt, rustfmt, etc.) where available.
- Add tests for bug fixes and new features whenever possible.
- Ensure all tests pass before submitting a PR.

---

## Making changes and commits

- Work on a branch dedicated to a single piece of work.
- Keep commits small and focused. Use clear, conventional commit messages. Examples:
  - `feat(auth): add JWT refresh token support`
  - `fix(api): handle missing fields in request body`
  - `chore(deps): update dependency xyz to v1.2.3`
- Rebase or merge the latest `main` branch into your branch before opening a PR to reduce merge conflicts and keep history tidy.

---

## Submitting a pull request

1. Push your branch to your fork:
```bash
git push origin feat/short-description
```
2. Open a PR against `Subhosjx/checkup` → branch `main`.
3. In the PR description, include:
   - What you changed and why.
   - Steps to reproduce / how to test the change locally.
   - Any relevant screenshots, logs, or benchmark results.
4. Link related issues (e.g., `Fixes #123`).
5. Be responsive to review feedback. Maintainers may request changes — please update your PR promptly.

Checklist to include in your PR description (if applicable):
- [ ] Code follows existing style and patterns
- [ ] Tests added/updated
- [ ] All tests pass locally
- [ ] Documentation updated (if necessary)

---

## Hacktoberfest guidance

- Quality over quantity: Hacktoberfest encourages meaningful contributions. Trivial, spammy, or low-effort PRs may be closed and will not be counted.
- For a PR to be counted for Hacktoberfest:
  - The PR must be accepted (merged), OR
  - A maintainer may add the `hacktoberfest-accepted` label to an approved PR that is not merged (this helps contributors receive credit).
- Make sure your contribution:
  - Solves a real problem or improves the project.
  - Includes tests or documentation updates where relevant.
  - Follows the repository's contribution rules and code of conduct.
- Maintainers: if you approve an unmerged PR but want the contributor to get Hacktoberfest credit, please add the `hacktoberfest-accepted` label once you’ve verified the change.

---

## Community & Code of Conduct

- Be respectful and inclusive. Read and follow the repository’s Code of Conduct (see `CODE_OF_CONDUCT.md` if present).
- Maintain a collaborative tone in discussions and reviews.
- Treat maintainers’ time with respect — many are volunteers.

---

## License & Contact

- By contributing, you agree that your contributions will be licensed under the project’s existing license (see `LICENSE`).
- For questions about contributions or Hacktoberfest eligibility, open an issue or mention @Subhosjx in a discussion or issue.

---

Thank you for taking part in Hacktoberfest and for helping improve checkup!
