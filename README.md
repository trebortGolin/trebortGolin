# 👋 Hi, I'm Robert

## 🤖 Building the Future of AI Agent Commerce

I'm the creator of **[Amorce](https://github.com/trebortGolin/agent-marketplace-demo)** - the security layer for AI agents.

---

## 🔥 Featured Project

### [AI Agent Marketplace Demo](https://github.com/trebortGolin/agent-marketplace-demo)

Watch two autonomous AI agents negotiate a $500 MacBook Pro sale with **cryptographic security**.

🎯 **What it demonstrates:**
- LangChain + CrewAI integration
- Ed25519 signatures on every transaction
- Human-in-the-loop approvals
- Trust Directory reputation system
- A2A Protocol compatibility

```python
# LangChain (2 lines of code)
from langchain_amorce import AmorceAgent
agent = AmorceAgent(llm=ChatOpenAI(), tools=[search], secure=True)

# CrewAI (1 decorator)
from crewai_amorce import secure_crew
@secure_crew
crew = Crew(agents=[...], tasks=[...])
```

---

## 📦 Amorce Ecosystem

### Framework Integrations
- **[langchain-amorce](https://github.com/trebortGolin/langchain-amorce)** - 2-line security for LangChain
- **[crewai-amorce](https://github.com/trebortGolin/crewai-amorce)** - 1-decorator for CrewAI crews
- **[autogpt-amorce-plugin](https://github.com/trebortGolin/autogpt-amorce-plugin)** - Zero-config AutoGPT plugin

### Core Infrastructure
- **[amorce-js-sdk](https://github.com/trebortGolin/amorce-js-sdk)** - TypeScript/JavaScript SDK (on npm)
- **[amorce_py_sdk](https://github.com/trebortGolin/amorce_py_sdk)** - Python SDK (on PyPI)
- **[amorce-console](https://github.com/trebortGolin/amorce-console)** - [Live management console](https://amorce-console-425870997313.us-central1.run.app)

---

## 🎯 The Problem I'm Solving

With Google's A2A Protocol and Anthropic's MCP, we have standards for agent communication. But they're missing **cryptographic trust**.

Amorce adds:
- ✅ Ed25519 signatures
- ✅ Human-in-the-loop approvals
- ✅ Trust Directory (reputation system)
- ✅ Transaction verification
- ✅ Fraud prevention

---

## 🚀 Tech Stack

**Languages**: TypeScript, Python, Go  
**Crypto**: Ed25519, libsodium  
**Frameworks**: Next.js, LangChain, CrewAI  
**Cloud**: Google Cloud Run, Cloud Build  
**Protocols**: A2A, MCP, HTTP/2

---

## 📊 Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=trebortGolin&show_icons=true&theme=dark)

---

## 🔗 Links

- **Demo**: [Agent Marketplace](https://github.com/trebortGolin/agent-marketplace-demo)
- **Console**: [amorce.io](https://amorce-console-425870997313.us-central1.run.app)
- **npm**: [@amorce/sdk](https://www.npmjs.com/package/@amorce/sdk)
- **PyPI**: [amorce-sdk](https://pypi.org/project/amorce-sdk/)

---

**Building the trust infrastructure for the agent economy** 🤖⚡
