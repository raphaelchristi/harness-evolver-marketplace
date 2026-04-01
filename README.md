# Harness Evolver — Plugin Marketplace

Claude Code plugin marketplace for [Harness Evolver](https://github.com/raphaelchristi/harness-evolver).

## Install

```
/plugin marketplace add raphaelchristi/harness-evolver-marketplace
/plugin install harness-evolver
```

## First-time setup

After installing the plugin, run `/evolver:setup` to configure LangSmith for your project.

If you don't have a LangSmith API key configured yet, run the full installer first:

```bash
npx harness-evolver@latest
```

## What's included

- **5 agents**: proposer, evaluator, critic, architect, testgen
- **4 skills**: `/evolver:setup`, `/evolver:evolve`, `/evolver:status`, `/evolver:deploy`
- **SessionStart hook**: auto-installs Python deps (langsmith, langsmith-cli) on every session

## Updates

Updates are automatic. When a new version is released, the plugin updates on your next Claude Code session.
