#### Agentic Development

I enjoy building software at the boundary between deterministic systems and AI-driven systems, and understanding complex technologies by rebuilding simplified versions of them from first principles.

My interests include agent workflows, retrieval systems, backend engineering, applied AI, system design, deployment, and infrastructure.

Many of my projects explore questions such as:

- When should a problem be solved with code?
- When should it be solved with an agent?
- How should both approaches interact safely?
- What architectural tradeoffs emerge when AI becomes part of the software stack?

**Technical Interests**
```text
Python
FastAPI
Agent Systems
RAG
LLMs
LangChain
SQLite
Linux
System Design
Backend Development
APIs
Git
```

#### What I'm Building Now

**OrderBuilder v2**

A redesign of the AI ordering pipeline that:

- Hardcodes order finalization outside the model
- Uses structured JSON outputs rather than conversational assembly
- Reduces agent complexity and increases determinism
- Improves reliability for production-style ordering workflows

**Fine-tuning Qwen2.5-Coder-1.5B-Instruct (Attempt #2)**

Current workflow:

- Generate synthetic training data programmatically
- Expand each training instance with multiple user prompt variations
- Use multiple model/temperature combinations for dataset generation
- Train using Unsloth on Camber-provided hardware through the GitHub Student Developer Pack
- Deploy the resulting model through an existing Hugging Face inference endpoint

Goal: produce a lightweight model specialized in menu-to-JSON order generation.

---

# Current Featured Projects

## 🍔 OrderBuilder

An AI-powered ordering platform that allows customers to build orders either through a traditional kiosk interface or through a conversational agent.

Repository: [kioskagentordermaker](https://github.com/faisalsardi-dev/kioskagentordermaker)

## ⛓️ OpenLedger

A simplified cryptocurrency implementation demonstrating wallet generation, transaction signing, balance tracking, and blockchain-style ledger verification.

Repository: [openledger](https://github.com/faisalsardi-dev/openledger)

## 🪙 ClickCrypto

A lightweight command-line cryptocurrency tracker that retrieves live market data directly from CoinGecko.

Repository: [clicrypto](https://github.com/faisalsardi-dev/clicrypto)

## 🤖 Leap-Aware Agent

A comparison of deterministic software architecture and LLM tool-calling workflows using leap-year-aware date calculations.

Repository: [leapawareagent](https://github.com/faisalsardi-dev/leapawareagent)
