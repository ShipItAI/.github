# ShipItAI

AI-powered code reviews for GitHub pull requests, powered by Claude.

ShipItAI automatically reviews your pull requests and posts inline comments directly on the lines of code that need attention — catching bugs, security issues, and suggesting improvements before your teammates even look at the PR.

## How It Works

1. Open a pull request
2. ShipItAI analyzes your changes with Claude
3. Receive a GitHub review with inline comments and a summary

No context switching. No copy-pasting code into chat windows. Actionable feedback integrated into your existing workflow.

## Two Ways to Use ShipItAI

### Self-Hosted (Free)

The core review engine is fully open source. Run it on your own infrastructure with Docker and PostgreSQL, using your own Anthropic API key.

- Full control over your data and infrastructure
- No per-developer fees
- Deploy with `docker compose up`

Get started: [**shipitai/shipitai**](https://github.com/shipitai/shipitai)

### Hosted via GitHub Marketplace ($5/mo per active developer)

Zero-setup hosted service — install the GitHub App, add your Anthropic API key, and you're done. We handle the infrastructure, you control the AI costs directly.

- One-click install from GitHub Marketplace
- No servers to manage
- 7-day free trial

Install: [**ShipItAI on GitHub Marketplace**](https://github.com/marketplace/shipitai)

## Features

- **Inline comments** on specific lines of code with actionable suggestions
- **CLAUDE.md support** — automatically reads your project context for smarter reviews
- **Configurable** per-repo via `.github/shipitai.yml` (triggers, exclusions, custom instructions)
- **Large PR support** — intelligent chunking for big diffs
- **Follow-up replies** — ask questions with `@shipitai` in PR comments
- **Contributor protection** — restricts auto-reviews to trusted contributors on public repos
- **Any language** — works with every programming language

## Repositories

| Repository | Description |
|---|---|
| [shipitai/shipitai](https://github.com/shipitai/shipitai) | Open source review engine — self-host with Docker + PostgreSQL |

## Links

- [Documentation](https://github.com/shipitai/shipitai#readme)
- [Self-Hosting Guide](https://github.com/shipitai/shipitai/blob/main/docs/self-hosting.md)
- [Configuration Examples](https://github.com/shipitai/shipitai/tree/main/examples)
- [GitHub Marketplace](https://github.com/marketplace/shipitai)
- [Website](https://shipitai.dev)
