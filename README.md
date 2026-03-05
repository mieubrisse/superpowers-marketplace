# Superpowers Marketplace

Curated Claude Code plugins for skills, workflows, and productivity tools.

This is a fork of [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace). The `superpowers` and `superpowers-dev` plugins point at [mieubrisse/superpowers](https://github.com/mieubrisse/superpowers) instead of the upstream repo. That fork disables git worktree isolation, which causes agents to operate in the wrong directory and break workflows ([obra/superpowers#583](https://github.com/obra/superpowers/issues/583)). All other plugins still point at obra's repos.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add mieubrisse/superpowers-marketplace
```

## Available Plugins

### Superpowers (Core)

**Description:** Core skills library with TDD, debugging, collaboration patterns, and proven techniques

**Categories:** Testing, Debugging, Collaboration, Meta

**Install:**
```bash
/plugin install superpowers@superpowers-marketplace
```

**What you get:**
- 20+ battle-tested skills
- `/brainstorm`, `/write-plan`, `/execute-plan` commands
- Skills-search tool for discovery
- SessionStart context injection

**Repository:** https://github.com/mieubrisse/superpowers

---

### Elements of Style

**Description:** Writing guidance based on William Strunk Jr.'s The Elements of Style (1918)

**Categories:** Writing, Documentation, Reference

**Install:**
```bash
/plugin install elements-of-style@superpowers-marketplace
```

**What you get:**
- `writing-clearly-and-concisely` skill
- Complete 1918 reference text (~12k tokens)
- All 18 rules for clear, concise writing
- Grammar, punctuation, and composition guidance

**Repository:** https://github.com/obra/the-elements-of-style

---

### Superpowers: Developing for Claude Code

**Description:** Skills and resources for developing Claude Code plugins, skills, MCP servers, and extensions

**Categories:** Development, Documentation, Claude Code, Plugin Development

**Install:**
```bash
/plugin install superpowers-developing-for-claude-code@superpowers-marketplace
```

**What you get:**
- `working-with-claude-code` skill with 42+ official documentation files
- `developing-claude-code-plugins` skill for streamlined development workflows
- Self-update mechanism for documentation
- Complete reference for plugin development, skills, MCP servers, and extensions

**Repository:** https://github.com/obra/superpowers-developing-for-claude-code

---

## Marketplace Structure

```
superpowers-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md                  # This file
```

## Support

- **Issues**: https://github.com/mieubrisse/superpowers-marketplace/issues
- **Core Plugin**: https://github.com/mieubrisse/superpowers
- **Upstream Marketplace**: https://github.com/obra/superpowers-marketplace

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
