<div align="center">

# 👋 Hey, I'm Ernani

### Building grounded verdicts for AI agents — and the people who run them

[Gecko](https://app.geckovision.tech) • [X](https://x.com/ernanibritto) • [LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)

</div>

---

## 🚀 What I'm Building

**[Gecko](https://app.geckovision.tech)** — a Knowledge-as-a-Service oracle for agentic workflows.

When an AI agent has to make a high-stakes call — *"is this trade worth it?"*, *"should I deposit into this vault?"* — a single model guess isn't enough. Gecko runs a 7-voice adversarial debate grounded in investor canon (Marks, Damodaran, Berkshire) + live on-chain data, and returns a structured verdict with surviving dissent and citations.

- **Verdict envelope** — verdict, confidence, dissent, citations, blocker questions
- **Cache-then-charge oracle** — agents query on cadence, not per-trade
- **x402-native pricing** — pay-per-call in USDC on Solana / Base
- **Claude Code skill distribution** — `Read app.geckovision.tech/skill.md` → bootstrap → use

---

## 💡 Why This Matters

Agents that act on money need oracles, not vibes. Today's AI ecosystem ships single-model answers, refusal disclaimers, and confident hallucinations on price / TVL / APY. Gecko is the opposite shape: **always answer, always cite, always show what your strongest critic said.**

---

## 🧠 Core Surfaces

### 1) `gecko_trade_research` — the oracle MCP tool
Adversarial 7-voice debate (analyst, critic, contrarian, risk, …) over a hybrid corpus: investor canon + protocol-native data + live market feeds. Output: verdict envelope with grounded dissent and structured citations.

### 2) `gecko-trade-agent` — runtime that consumes the oracle
Advisor-mode in v0.1 (alerts), trader-mode in v0.2 (executes through neutral adapters — SendAI / OKX / Backpack). Cache-then-charge on `idea_hash` so agents call the oracle on cadence + triggers, not per-trade.

### 3) `gecko-trade-coach` — conversational strategy builder
Takes a user from *"I want to make money in DeFi"* to a schema-validated strategy spec the agent can run.

---

## 🛠️ Tech Stack

```python
stack = {
    "core":     ["Python 3.11+", "uv workspace", "FastAPI", "MCP"],
    "models":   ["OpenAI GPT-4o", "Anthropic Sonnet 4.6 (judge)", "AutoGen GroupChat"],
    "data":     ["MongoDB Atlas (Vector Search)", "Cohere Rerank"],
    "payments": ["x402 on Solana / Base", "USDC", "frames.ag + CDP"],
    "delivery": ["Claude Code skills", "Vercel", "AWS ECS"],
    "sources":  ["Pyth", "Helius", "Birdeye", "Jupiter", "Tavily"],
}
```

---

## 🎯 Current Focus

- [ ] V1 ship-gate on grounded trade verdicts (6-dim rubric — accuracy, citation relevance, provider coverage, hallucination, dissent grounding, calibration)
- [ ] Investor-canon corpus depth (Oaktree memos, NYU Stern, Berkshire 1977–2024 — public-domain only)
- [ ] First 10 outside-network users running `gecko_trade_research` weekly
- [ ] OKX OnchainOS *Skill Quality* submission

---

## 🤝 Looking For

| Who | Why |
|-----|-----|
| **Crypto-native traders / yield farmers** | Stress-test verdicts on real positions |
| **Agent builders (Claude Code, OKX, SendAI)** | Compose `gecko_trade_research` into your skill |
| **Investor-letter / research nerds** | Tell me which canon sources I'm missing |
| **x402 / Solana payment infra** | Integrate the oracle as a paid call |

---

## 💬 Let's Talk

Building agentic finance, trade-oracle infra, or grounded-verdict primitives? Interested.

**DM me on [X](https://x.com/ernanibritto)** or **[LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)**

<div align="center">

---

*"Answer the question. Cite your work. Show what your strongest critic said."*

</div>
