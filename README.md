# 👋 Hi, I'm Robert

## 🤖 Building the Trust Layer for AI Agent Communication

I'm the creator of **[Amorce](https://amorce.io)** — **One Trust Layer. Any Agent. Any Framework.**

Connect LangChain, CrewAI, n8n, AutoGPT, ChatGPT, Claude, Gemini — in 5 minutes.

---

## 🔥 Featured Project

### [Amorce - The Universal Trust Layer](https://amorce.io)

The open-source protocol that enables cross-framework agent communication with cryptographic security.

🎯 **What Amorce does:**
- **n8n workflow calls CrewAI crew** — Signed request, verified response
- **LangChain agent discovers AutoGPT** — Cross-framework discovery via ANS
- **ChatGPT finds your agent** — LLM discoverability via MCP
- **Human approval for $5000 booking** — Built-in HITL

---

## 📦 The Amorce Ecosystem

### Framework Integrations

| Package | Framework | Install |
|---------|-----------|---------|
| **[n8n-nodes-amorce](https://www.npmjs.com/package/n8n-nodes-amorce)** | n8n | `npm install n8n-nodes-amorce` |
| **[langchain-amorce](https://github.com/trebortGolin/langchain-amorce)** | LangChain | `pip install langchain-amorce` |
| **[crewai-amorce](https://github.com/trebortGolin/crewai-amorce)** | CrewAI | `pip install crewai-amorce` |
| **[autogpt-amorce-plugin](https://github.com/trebortGolin/autogpt-amorce-plugin)** | AutoGPT | Zero-config plugin |

### Core SDKs

| Package | Language | Install |
|---------|----------|---------|
| **[@amorce/sdk](https://www.npmjs.com/package/@amorce/sdk)** | TypeScript/JS | `npm install @amorce/sdk` |
| **[amorce-sdk](https://pypi.org/project/amorce-sdk/)** | Python | `pip install amorce-sdk` |
| **[@amorce/mcp-server](https://www.npmjs.com/package/@amorce/mcp-server)** | LLM Discovery | `npx @amorce/mcp-server` |

### Infrastructure

- **[amorce](https://github.com/trebortGolin/amorce)** - Core runtime & orchestrator
- **[amorce-trust-directory](https://github.com/trebortGolin/amorce-trust-directory)** - Agent registry & ANS
- **[amorce-console](https://github.com/trebortGolin/amorce-console)** - [Live at amorce.io](https://amorce.io)

---

## 🎯 The Problem I'm Solving

AI agents from different frameworks can't talk to each other securely. Amorce adds:

- ✅ **Ed25519 signatures** — Cryptographic proof of identity
- ✅ **Cross-framework calls** — n8n ↔ LangChain ↔ CrewAI ↔ AutoGPT
- ✅ **LLM discovery** — ChatGPT, Claude, Gemini can find your agent
- ✅ **Human-in-the-loop** — Approval workflows for sensitive actions
- ✅ **5-minute integration** — No custom auth code needed

---

## 🚀 Quick Start

```python
# Python SDK
pip install amorce-sdk

from amorce import verify_request

# Verify incoming requests — 2 lines!
verified = verify_request(headers, body)
print(f"Verified from: {verified.agent_id}")
```

```typescript
// TypeScript SDK
npm install @amorce/sdk

import { verifyRequest } from '@amorce/sdk';
const verified = await verifyRequest({ headers, body });
```

---

## 📊 Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=trebortGolin&show_icons=true&theme=dark)

---

## 🔗 Links

- **Website**: [amorce.io](https://amorce.io)
- **Registry**: [amorce.io/registry](https://amorce.io/registry)
- **Docs**: [amorce.io/docs](https://amorce.io/docs)
- **npm**: [@amorce/sdk](https://www.npmjs.com/package/@amorce/sdk)
- **PyPI**: [amorce-sdk](https://pypi.org/project/amorce-sdk/)

---

**One Trust Layer. Any Agent. Any Framework.** 🤖⚡
