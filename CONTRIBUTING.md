# Contributing to Free-Editor of Shared IDE

First off, thank you for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. Please read the relevant section before making your contribution. This helps maintainers and smooths out the experience for everyone involved. We look forward to your contributions! 🎉

- [Code of Conduct](#code-of-conduct)
- [Question or Problem?](#question-or-problem)
- [Features vs Bugs](#features-vs-bugs)
- [For all Issues](#for-all-issues)
- [Submitting an Issue](#submitting-an-issue)
- ['Needs Triage' Issue Label](#needs-triage-issue-label)
- [Submitting a Pull Request (PR)](#submitting-a-pull-request-pr)
- [Reviewing a Pull Request](#reviewing-a-pull-request)
- [Local Setup for Development](#local-setup-for-development)
- [Coding Rules](#coding-rules)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Testing](#testing)

If you enjoy the project but don’t have time to contribute, here are other ways you can support us:
- Star the project
- Share the project on social media
- Mention the project in your project's README
- Recommend the project to friends, colleagues, and at local meetups

## Code of Conduct

This project and everyone participating is governed by the [Code of Conduct](/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report any unacceptable behavior to the repository maintainers.

## Question or Problem?

For general support, please do not open GitHub issues. Use Discussions for support-related questions, and we’ll be happy to help.

## Features vs Bugs

Understand the difference between a feature and a bug when creating issues:
- **Feature**: A request to implement something new.
- **Bug**: Fixing something that’s not working as expected.

## For all Issues

Before working on an issue, open a discussion to outline your proposal so it can be reviewed and coordinated. This helps avoid duplication of effort and ensures smooth collaboration.

## Submitting an Issue

Before opening an issue, please search existing issues to check if the same problem has already been raised. Provide a minimal example of the issue for bug reports to help maintainers identify and fix the problem quickly.

**Do not erase** the issue template! Use the provided template to maintain consistency and clarity across all issues.

## 'Needs Triage' Issue Label

All new issues are labeled "needs triage" to be reviewed by maintainers. Once reviewed, this label will be removed, and the issue will be prioritized and assigned.

## Submitting a Pull Request (PR)

Before submitting a pull request (PR), ensure the following:

1. **Search** the repository for existing open or closed PRs that relate to your submission to avoid duplication.
2. [**Fork**](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) the repository.

3. **Create a new branch** for your work:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes, ensuring they follow the repository's tech stack:
- AnalogJS + Angular Material UI
5. Commit your changes:
```
git commit -m "Add description of your changes"
```
6. **Push** your changes to your forked repository:  
```
git push origin feature/your-feature-name
```
7. Open a **Pull Request(PR)** from your fork's branch to the main repository.

Use the PR template provided and make sure your PR follows the format of existing merged PRs.

## Reviewing a Pull Request
The maintainer(s) reserve the right to reject pull requests that do not meet the project's contribution guidelines. All PRs must be reviewed and approved by a maintainer before they can be merged.

## Local Setup for Development

To set up the project locally, follow these steps:

1. Install dependencies:
```bash
npm install
```
2. Run the development server:
```
npm start
```
This will launch the `free-editor` app in development mode on your local machine.

This will launch the free editor in development mode on your local machine.


## Coding Rules
- Maintain consistency with the project's existing file structure and code style.
- Use AnalogJS’s file-based routing to manage routes within the project. Pages and services should follow this routing structure for consistency.
- Follow SCSS guidelines for styling, using relative measurements like `rem`, `vh`, or `%` instead of `px`.

## Commit Message Guidelines

To maintain a clear and organized version history, we follow a standardized commit message convention. This ensures that each commit provides valuable information about the changes made. Please adhere to the following guidelines when crafting your commit messages:

### Feature:

```
feat(component): add new feature X
```

### Bug Fix:

```
fix(component): resolve issue with Y
```

### Documentation Update:

```
docs(readme): update installation instructions
```

### Code Refactor:

```
refactor(service): restructure data fetching logic
```

### Performance Improvements:

```
perf(api): optimize data retrieval for faster response
```

### Test:

```
test(component): add unit tests for feature Z
```

### Build:

```
build(pipeline): update dependencies and build scripts
```

### Chore (Release):

```
chore: prepare for version 1.0.0 release
```

### Revert

```
revert: revert changes from commit abc123
```

Ensure that your commit messages are descriptive and helpful for understanding the changes introduced.

## Testing
When contributing to the project, two types of testing are essential:

1. **Programmatic Tests**: These are automated tests that ensure your code does not break existing functionality. All programmatic tests must pass before submitting a pull request. You can run the tests locally with the following command:

```
npm test
```
2. **Functional Testing**: This involves manually verifying that the feature or bug fix you worked on actually behaves as expected within the editor. This includes checking the user interface, ensuring buttons and features work, and confirming that the intended changes function properly when tested in a real-world scenario.

Both types of testing are important to ensure that new changes are reliable and meet the project's quality standards.

### Mandatory Compliance with [Coding Rules](#coding-rules) and [Commit Message Guidelines](#commit-message-guidelines) for PR Merges

Kindly ensure that all pull requests strictly adhere to our Coding Rules and Commit Message Guidelines. Non-compliant PRs must be adjusted prior to acceptance.

## Reviewer Accountability

Reviewers who approve PRs not in alignment with the [Coding Rules](#coding-rules) and [Commit Message Guidelines](#commit-message-guidelines) may face restrictions on their approval privileges.

## Thank You!
Your contributions help shape the future of Free-Editor, and we’re excited to see what improvements and innovations you bring. Whether you’re fixing a bug, adding a new feature, or enhancing the codebase, your input is invaluable. Together, we’re building a tool that empowers developers and brings real value to the community.

We truly appreciate your effort and look forward to working with you to make Free-Editor the best it can be! 🚀





