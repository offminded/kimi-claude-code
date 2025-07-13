# Kimi Claude Code

## Quick Installation

1. Get your API Key from moonshot.

Moonshot Platform: [Kimi Open Platform](https://platform.moonshot.cn/)

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/offminded/kimi-claude-code/refs/heads/main/install.sh)"
```

3. Start using Claude Code.

```shell
claude
```

## What the installer does

The installation script automatically:
1. Checks and installs Node.js (v18+) if needed
2. Installs Claude Code globally via npm
3. Configures Claude Code to skip onboarding
4. Prompts for your Moonshot API key
5. Sets up environment variables to redirect API calls to Kimi's servers

## Manual Config
To configure manually, set these environment variables:

```bash
export ANTHROPIC_BASE_URL=https://api.moonshot.cn/anthropic/
export ANTHROPIC_API_KEY=sk-123
```
