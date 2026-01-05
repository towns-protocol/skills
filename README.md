# Towns Bot Skill

A Claude Code plugin providing comprehensive knowledge for building Towns Protocol bots.

## Installation

### For HereNotThere team members

Add to your `~/.claude/settings.json`:

```json
{
  "plugins": {
    "marketplaces": ["github:HereNotThere/towns-skill-marketplace"]
  }
}
```

Then install:
```bash
/plugin install towns
```

### Direct installation

```bash
claude --plugin-dir /path/to/towns-skill
```

## Usage

Invoke the skill with `/towns:bots` or let it trigger automatically when working on Towns bot development:

- "Create a Towns bot with slash commands"
- "Add message handling to my Towns bot"
- "How do I send mentions in a Towns bot?"
- "Set up interactive forms in my bot"

## What's Included

- SDK initialization and configuration
- Event handlers (messages, commands, reactions, tips)
- Messaging API (mentions, threads, attachments, formatting)
- Interactive components (forms, buttons, transactions)
- Blockchain operations (read/write contracts, transaction verification)
- Deployment guides (local dev, Render.com, graceful shutdown)
- Debugging patterns and common mistakes

## Resources

- [Towns Developer Portal](https://app.towns.com/developer)
- [Towns Documentation](https://docs.towns.com/build/bots)
- [@towns-protocol/bot SDK](https://www.npmjs.com/package/@towns-protocol/bot)
