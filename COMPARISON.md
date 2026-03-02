# Claws Technical Comparison

A multi-dimensional comparison of the "Claw" family of autonomous AI agents.

| Feature | OpenClaw | PaeanClaw | ZeroClaw | NanoClaw | PicoClaw | IronClaw |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Language** | TypeScript | TypeScript | Rust | TypeScript | Go | Rust |
| **Footprint** | Large | Medium | Ultra-Light (<5MB) | Lightweight | Ultra-Light (<10MB) | Medium (Security-focused) |
| **Runtime** | Node.js | Node.js | Native Binary | Node.js (Agents SDK) | Native Binary | WASM Sandboxed |
| **Primary Focus** | General Purpose Assistant | MCP & Payments | Performance & Security | Container Isolation | Low-cost Hardware | Capability-based Security |
| **Messaging** | WhatsApp, Slack, etc. | MCP Interfaces | 22+ Providers | WhatsApp | Telegram, Discord | Enterprise/Security |
| **Storage** | SQL / Local | SQL / MCP | Encrypted Local | Local | Local | Secure WASM Storage |

## Multi-dimensional Analysis

### 1. Performance & Efficiency
- **PicoClaw** & **ZeroClaw** are the clear winners for edge devices, with boot times under 1 second and minimal RAM usage.
- **OpenClaw** and **PaeanClaw** provide more rich feature sets at the cost of higher resource requirements.

### 2. Security Architecture
- **IronClaw** uses WASM sandboxing to prevent memory corruption, making it the most secure for untrusted skills.
- **NanoClaw** focuses on Linux container isolation for agent execution.
- **ZeroClaw** provides local encryption of secrets and a full security checklist.

### 3. Extensibility
- **PaeanClaw** is optimized for **Model Context Protocol (MCP)**, allowing it to seamlessly integrate with a vast ecosystem of tools.
- **OpenClaw** relies on its own "Skill" system which is highly mature but less standardized than MCP.

### 4. Deployment Environment
- **AnyClaw** is unique in its focus on non-root Android deployment.
- **Moltworker** provides an interesting approach using Cloudflare Workers for edge deployment.
