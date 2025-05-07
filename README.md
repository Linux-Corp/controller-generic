# Dependabot Demo Repo

This repository contains two minimal projects to demonstrate Dependabot security updates:

- `js-npm/`: A simple Node.js (npm) project
- `java-maven/`: A simple Java (Maven) project

Dependabot is configured via `.github/dependabot.yml` to check for security updates in both projects and create pull requests automatically.

## How to Use

1. Push this repository to GitHub.
2. Ensure GitHub Dependabot is enabled (it is by default for public repos).
3. When a dependency update is available, Dependabot will create a pull request for you.
4. Review and merge the PRs as needed.

## Files

- `.github/dependabot.yml`: Dependabot configuration
- `js-npm/package.json`: npm dependencies
- `java-maven/pom.xml`: Maven dependencies