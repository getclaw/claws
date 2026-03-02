# Awesome Claws: Skills & MCPs 🛠️

A curated list of skills, plugins, and Model Context Protocol (MCP) servers to extend the capabilities of your Claw-family autonomous agents.

## Table of Contents
- [Skill Directories](#skill-directories)
- [Official Skills](#official-skills)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [Security Notice](#security-notice)

---

## Skill Directories

### [ClawHub](https://github.com/openclaw/clawhub)
The public registry and skill directory for OpenClaw. It functions as the central hub where users can publish, version, and search for text-based agent skills.
- **Features**: Semantic search via embeddings, version control, and changelogs.

### [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)
A community-curated list aggregating and categorizing skills sourced from ClawHub and other community repositories.

---

## Official Skills

### [OpenClaw Skills Archive](https://github.com/openclaw/skills)
The official archive containing versions of skills originally available on the legacy Clawdhub.com registry.
- **Languages Support**: Python, JavaScript, TypeScript.

---

## Model Context Protocol (MCP)

MCP allows secure, standardized communication between AI agents and external tools/data sources. The Claw ecosystem (particularly PaeanClaw) is rapidly adopting MCP.

### [Paean Pay MCP](https://github.com/paean-ai/paean-pay-mcp)
A specialized MCP server that enables AI agents to handle financial transactions.
- **Capabilities**: Wallet management, balance checking, payment request creation, and USDC transfers.
- **Networks**: Base, Solana.
- **Compatible Clients**: PaeanClaw, OpenPaean CLI, Claude Desktop, Cursor.

---

## Security Notice ⚠️

> [!CAUTION]
> Always audit the source code of any third-party skill or plugin before installing it into your agent system.
> Malicious skills have been identified in the wild that attempt to execute unauthorized commands or steal environment variables. Rely on established mechanisms like WASM sandboxing (e.g., IronClaw) or containerization (e.g., NanoClaw) for untrusted code.
