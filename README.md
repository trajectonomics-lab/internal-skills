# Trajectonomics Lab Internal Skills

Internal AI coding agent skills for the Trajectonomics Lab ecosystem, managed via [skills.sh](https://skills.sh/) (`npx skills`).

## Available Skills

- **`pick-the-issue`**: Discovers open GitHub issues across the repository or organization, filters out blocked issues and issues actively handled by existing T3 Code sessions, provides an executive summary, and routes the work through Matt Pocock's skills framework (`ask-matt`) to advise on the exact commands and workflow.

## Installation

Install into any Trajectonomics repository using the `skills` CLI:

```bash
# Add to the current repository
npx skills add trajectonomics-lab/internal-skills -y

# Update to latest version
npx skills update -p -y
```
