# 📊 Claws Technical Comparison

A multi-dimensional comparison of the "Claw" family of autonomous AI agents, designed to help developers and users choose the right framework for their needs.

## Quick Reference Matrix

| Feature | OpenClaw | PaeanClaw | 0Claw / ZeroClaw | NanoClaw | PicoClaw | IronClaw |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Primary Language** | TypeScript | TypeScript | Rust | TypeScript | Go | Rust |
| **Memory Footprint** | Large (>150MB) | Medium | Ultra-Light (<5MB) | Lightweight | Ultra-Light (<10MB)| Medium |
| **Execution Runtime**| Node.js | Node.js | Native Binary | Node.js (Containers) | Native Binary | WASM Sandbox |
| **Primary Focus** | General Assistant | MCP & Payments | Speed & Efficiency | Container Safety | IoT & Edge | Execution Security |
| **Extensibility** | Custom Skills | MCP Servers | Provider Agnostic | Anthropic SDK | Basic Handlers | Capability system |
| **Storage Engine** | SQL / Local Files | SQL / MCP | Encrypted Local | Local | Local | Secure WASM FS |

---

## Deep Dive Dimensions

### 1. Performance & Hardware Efficiency
*   🥇 **PicoClaw** & **0Claw (ZeroClaw)** are the undisputed leaders for resource-constrained environments (e.g., Raspberry Pi, cheap VPS). With sub-second boot times and memory usage often peaking under 10MB, they are ideal for "always-on" micro-agents.
*   **OpenClaw** requires a full Node.js environment and significantly more memory, making it better suited for standard desktop or cloud deployments.

### 2. Security Architecture
Executing LLM-generated code locally presents a massive security risk. Different projects handle this differently:
*   🛡️ **IronClaw (NEAR AI)**: Most secure. Uses WebAssembly (WASM) to strictly sandbox execution, preventing agents from accessing the host filesystem or network without explicit capability grants.
*   📦 **NanoClaw**: Highly secure. Isolates agent execution within standard Linux containers (Docker/Podman), restricting blast radius.
*   🔒 **0Claw**: Focuses on data security at rest, providing native local encryption for API keys and secrets.
*   ⚠️ **OpenClaw**: Historically allowed direct shell access, which requires careful auditing of installed skills.

### 3. Extensibility Standards
*   🔌 **PaeanClaw**: Leads the pack in adopting the **Model Context Protocol (MCP)**. This allows it to instantly connect to standard tools without custom integration code.
*   🛠️ **OpenClaw**: Relies on a mature but proprietary "Skill" system (via ClawHub). While there are many skills available, they are specific to this ecosystem.

### 4. Deployment Environments
*   📱 **AnyClaw**: Unique focus on un-rooted Android environments, bringing autonomous capabilities directly to smartphones.
*   ☁️ **Moltworker**: Explores serverless edge execution by targeting Cloudflare Workers, eliminating the need for persistent servers.
