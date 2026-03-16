# Contributing to Smasage 🤝

First off, thank you for considering contributing to Smasage! It's people like you that make Smasage such a great tool.

## How Can I Contribute?

### Reporting Bugs

- Check the [issues](https://github.com/your-username/smasage/issues) to see if it has already been reported.
- If not, create a new issue. Clearly describe the bug, include steps to reproduce, and specify your environment.

### Suggesting Enhancements

- Open a new issue with the tag "enhancement".
- Explain the feature and how it would benefit users.

### Pull Requests

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Ensure the test suite passes (`npm test` or `cargo test`).
4. Make sure your code lints.
5. Issue a pull request!

## Development Setup

### Project Structure

- `/frontend`: Next.js application (TypeScript + Vanilla CSS).
- `/agent`: Node.js backend using OpenClaw.
- `/contracts`: Soroban smart contracts in Rust.

### Branching Policy

- `main`: Production-ready code.
- `development`: Integration branch for features.
- `feature/*`: Specific feature development.

## Style Guidelines

### Code Formatting

- **TypeScript**: We follow standard ESLint configurations.
- **CSS**: Use Vanilla CSS. Focus on maintaining the premium, dark-themed aesthetic.
- **Rust**: Use `cargo fmt` before committing.

### Commit Messages

- Use the imperative mood ("Add feature" not "Added feature").
- Keep the subject line under 50 characters.

## Code of Conduct

We are committed to providing a friendly, safe, and welcoming environment for all, regardless of level of experience, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion, or nationality.

## Questions?

Join our community or open an issue for discussion!
