# My Agent Skills

A collection of AI agent skills installed and configured for my agent.

## Included Skills

### Proactive Agent (v3.1.0)

Transform AI agents from task-followers into proactive partners that anticipate needs and continuously improve.

**Author:** halthelobster
**Modifier:** tommynurwantaro

**The Three Pillars:**

- **Proactive** - Creates value without being asked, anticipates needs, reverse prompting
- **Persistent** - Survives context loss via WAL Protocol, Working Buffer, and Compaction Recovery
- **Self-improving** - Gets better at serving you over time with self-healing and guardrails

**Key Features:**
- WAL Protocol - Write critical details BEFORE responding
- Working Buffer Protocol - Captures every exchange in the danger zone
- Compaction Recovery - Knows exactly how to recover after context loss
- Security Hardening - Protection against injection attacks and context leakage
- Relentless Resourcefulness - Tries 10 approaches before giving up
- Autonomous Crons - Background tasks that execute without main session attention

## Installation

Each skill is structured for easy installation. Copy the skill folder to your agent's skills directory.

```
cp -r proactive-agent /path/to/your/agent/skills/
```

## Project Structure

```
my-agent-skills/
├── README.md
└── proactive-agent/
    ├── SKILL.md           # Main skill definition
    ├── _meta.json         # Metadata (owner, version, etc.)
    ├── assets/            # Supporting files
    │   ├── AGENTS.md      # Operating rules and workflows
    │   ├── HEARTBEAT.md   # Periodic self-improvement checklist
    │   ├── MEMORY.md      # Long-term memory template
    │   ├── ONBOARDING.md  # First-run setup guide
    │   ├── SOUL.md        # Identity and principles
    │   ├── TOOLS.md       # Tool configurations
    │   └── USER.md        # Human's context template
    ├── references/        # Documentation
    │   ├── onboarding-flow.md
    │   └── security-patterns.md
    └── scripts/           # Utility scripts
        └── security-audit.sh
```

## Quick Start (Proactive Agent)

1. Copy assets to your workspace: `cp proactive-agent/assets/*.md ./`
2. Your agent detects `ONBOARDING.md` and offers to get to know you
3. Answer questions (all at once, or drip over time)
4. Agent auto-populates USER.md and SOUL.md from your answers
5. Run security audit: `./proactive-agent/scripts/security-audit.sh`

## License

Each skill has its own license. See individual SKILL.md files for details.

- **Proactive Agent:** MIT License

## Credits

- **Proactive Agent:** Created by [Hal 9001](https://x.com/halthelobster) - Part of the Hal Stack
