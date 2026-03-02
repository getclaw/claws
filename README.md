<div align="center">
  <h1>Awesome Claws 🦞</h1>
  <p><i>A curated list of awesome open-source AI agents, assistants, and frameworks in the "Claw" family.</i></p>
  
  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
  [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
</div>

Inspired by the original OpenClaw, these projects focus on autonomy, personal productivity, minimal footprint, and extensible AI infrastructure.

---

## 📑 Table of Contents

- [The Original](#the-original)
- [Ecosystem Variants](#ecosystem-variants)
  - [Frameworks & Core](#frameworks--core)
  - [Mobile & Portable](#mobile--portable)
  - [Lightweight & Fast](#lightweight--fast)
  - [Security Focused](#security-focused)
- [Skills & Extensions](#skills--extensions)
- [Technical Comparison](#technical-comparison)
- [Contributing](#contributing)
- [License](#license)

---

## 👑 The Original

### [OpenClaw](https://github.com/openclaw/openclaw)
> The pioneer of the ecosystem. A free and open-source autonomous AI agent designed to be a proactive personal assistant.

- **Stack**: TypeScript / Node.js
- **Key Features**: Proactive task scheduling (cron jobs), persistent memory, multi-platform messaging integrations (WhatsApp, Telegram, Slack, iMessage).
- **Architecture Note**: Relies heavily on a custom skill system and direct shell access for executing tasks.

---

## 🧩 Ecosystem Variants

### Frameworks & Core

#### [PaeanClaw](https://github.com/paean-ai/paeanclaw)
> A modular and extensible implementation focusing on specialized skill sets and financial integrations.
- **Highlights**: First-class support for MCP (Model Context Protocol) servers, integrated stablecoin payment flows, and enterprise-ready agent abstractions.

#### [0Claw (ZeroClaw)](https://github.com/paean-ai/0claw)
> A high-performance, Rust-based implementation from the Paean AI team.
- **Highlights**: Extremely low-latency, minimal resource consumption (<5MB memory), and blazing fast startup (<10ms). Supports 22+ LLM providers.

#### [Moltworker](https://github.com/moltworker/moltworker)
> A cloud-native variant designed specifically for edge computing.
- **Highlights**: Optimized for deployment on Cloudflare Workers, providing a cloud-hosted but completely self-controlled agent environment.

---

### Mobile & Portable

#### [AnyClaw](https://github.com/paean-ai/anyclaw)
> The bridge to mobile autonomy.
- **Highlights**: Bundles Linux environments directly onto Android devices without requiring root access, enabling true on-device assistant capabilities.

#### [PicoClaw](https://github.com/picoclaw/picoclaw)
> An ultra-portable Go-based agent built for edge devices.
- **Highlights**: Boot time under 1 second, uses less than 10MB of RAM. Perfect for Raspberry Pi and RISC-V platforms.

---

### Lightweight & Fast

#### [NanoClaw](https://github.com/qwibitai/nanoclaw)
> An ultra-lightweight and secure alternative utilizing containerization.
- **Highlights**: Focuses on a highly readable codebase, Linux container isolation for executing agent tasks securely, and native WhatsApp integration.

#### [Nanobot](https://github.com/nanobot-ai/nanobot)
> A minimalist Python-based agent originating from HKU research.
- **Highlights**: 99% smaller than the original OpenClaw codebase, providing core functionality (web search, memory) on minimal hardware.

---

### Security Focused

#### [IronClaw](https://github.com/near-ai/ironclaw)
> A Rust-based implementation developed by NEAR AI prioritizing execution safety.
- **Highlights**: Utilizes WebAssembly (WASM) sandboxing to prevent memory corruption and enforces a strict capability-based security model for all agent skills.

---

## 🔌 Skills & Extensions

The Claw ecosystem is highly extensible. Discover skills, plugins, and MCP servers to power up your agent:

👉 **[View the Skills & MCPs Directory](./SKILLS_AND_MCPS.md)**

---

## 📊 Technical Comparison

Need help deciding which variant to use? We've compiled a multi-dimensional technical comparison across language, footprint, security, and extensibility.

👉 **[View the Technical Comparison](./COMPARISON.md)**

---

## 🤝 Contributing

Contributions are welcome! If you know of a "Claw" variant, skill, or project that belongs here:

1. Fork this repository.
2. Add your project to the relevant category in `README.md` or `SKILLS_AND_MCPS.md`.
3. Submit a Pull Request with a brief description.

Please ensure the project is open-source, actively maintained, and follows the community's standards for autonomy.

## 📄 License

This list is licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
