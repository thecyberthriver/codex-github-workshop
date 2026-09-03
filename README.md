# Build & Ship with AI — Workshop Materials

A hands-on, 1-hour workshop on using **Codex** + **GitHub** to create a real project and publish it to GitHub — and be able to explain and verify what shipped.

## 📄 Installation Guide

Set up everything before (or at the start of) the workshop:

**➡️ [Codex-GitHub-Workshop-Installation-Guide.pdf](Codex-GitHub-Workshop-Installation-Guide.pdf)**

Covers, step by step:

- Accounts & prerequisites (GitHub, ChatGPT, Chrome)
- ChatGPT desktop app + opening **Codex**
- **GitHub CLI** (`gh`) install + sign-in
- **Git** install & identity
- The **Codex Chrome extension**
- *(Optional)* the **Codex CLI** — macOS native, Windows via WSL2
- *(Optional)* connecting the **GitHub MCP** server to Codex
- Moving between conversations (`codex resume`, `/clear`, `/rename`, `/agent`)
- Your first project: build with Codex, push with GitHub CLI
- Verification checklist + troubleshooting

## Credential safety

Never paste a password or token into source code, a README, a prompt, or a committed `.env` file. Prefer browser sign-in or environment variables. If a secret is exposed, **revoke/rotate it** — deleting the file is not enough.
