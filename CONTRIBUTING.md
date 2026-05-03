# Contributing to [PROJECT NAME]

First off, thank you for considering contributing to Still Systems! It's people like you that make our tools better for everyone.

## 📋 Standards

This repository adheres to the [Still Systems Global Contributing Guidelines](https://github.com/stillsystems/.github/blob/main/CONTRIBUTING.md). Please review them before starting work.

### Local Development Flow

1. **Fork the repository** on GitHub.
2. **Clone your fork** locally: `git clone https://github.com/YOUR_USERNAME/[PROJECT NAME].git`
3. **Create a branch** for your work: `git checkout -b feat/your-feature-name`
4. **Implement your changes** and add tests.
5. **Verify everything passes**:
   - `npm test` (or `go test ./...`)
   - `npm run lint` (or `golangci-lint run`)
6. **Commit with impact**: We use [Conventional Commits](https://www.conventionalcommits.org/).
   - `feat: add awesome new capability`
   - `fix: resolve crash in edge case`
7. **Push to your fork** and open a Pull Request.

## 🧪 Testing Policy

We maintain a high bar for quality. All PRs must:
- Maintain or increase existing code coverage.
- Pass all CI checks.
- Include unit tests for any new logic.

## 💬 Communication

- **Bugs**: Use the [Bug Report](https://github.com/stillsystems/[PROJECT NAME]/issues/new?template=bug_report.yml) template.
- **Features**: Use the [Feature Request](https://github.com/stillsystems/[PROJECT NAME]/issues/new?template=feature_request.yml) template.

---
🧱 **Still Systems** — Tools engineered for real-world conditions.
