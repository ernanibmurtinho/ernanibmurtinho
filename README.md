<div align="center">

# 👋 Hey, I'm Ernani

### Making any API agent-usable — first-call-correct, no integration code

[Gecko](https://geckovision.tech) • [gecko-surf](https://github.com/GeckoVision/gecko-surf) • [X](https://x.com/ernanibritto) • [LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)

</div>

---

## 🚀 What I'm Building

**[Gecko](https://geckovision.tech)** — the **API comprehension layer for agents**. Point an agent at any API — even one behind human-shaped docs and a paywall — and it finds the right call, makes it correctly the first time, and runs. No client to write, no guessing whether the agent is calling it right.

> *Docs and endpoints are built for humans. Gecko translates an API's surface into question-shaped, first-call-correct agent tools — and handles the auth handshake the docs don't explain.*

The engine — **[`gecko-surf`](https://github.com/GeckoVision/gecko-surf)** (open-source, on PyPI) — turns any OpenAPI into first-call-correct MCP tools:

```bash
curl -fsSL https://get.geckovision.tech | bash
gecko <openapi-url>          # → comprehension summary + a one-click "add to Claude/Cursor"
```

---

## 💡 Why This Matters

A coding agent can one-shot a popular API. It can't one-shot the **Nth *painful* one** — long-tail, messy, poorly-documented, often paywalled. It picks the wrong endpoint, misplaces the credential, sends a UI amount where atomic units are required, forgets the idempotency key. Each miss is a failed call, a retry, a burned credit. Gecko replaces guess-and-retry with first-call-correct comprehension — and stays correct as the API drifts.

---

## 🧠 What I ship

**`gecko-surf` — the comprehension engine.** Ingest an OpenAPI surface → question-shaped, first-call-correct agent tools (auth hidden, units / placement / idempotency resolved), served over MCP. A `$0` **recorded mode** simulates the call offline before a cent moves — test it like Surfpool tests the chain, but for the API.

**Comprehension showcases.**
- **Surfpool** — comprehend its `surfnet_*` cheatcode RPC so an agent drives the validator correctly.
- **Jito · Helius · Jupiter · the CLMM protocols** — first-call-correct playbooks for the painful Solana/crypto APIs.
- **Payments** — verify a charge is first-call-correct (right centavos, idempotency, auth) *before* it charges.

**The three verbs.** APIs get **PAID** (rails), skills get **DISTRIBUTED** (marketplaces), **APIs get USED** (Gecko — comprehension). We compose on x402 / MCP / pay.sh — not a payment rail, not a marketplace.

---

## 🛠️ Tech

```python
stack = {
    "engine":   ["Python 3.11+", "uv", "MCP (Streamable-HTTP)", "stdlib-first"],
    "delivery": ["PyPI: gecko-surf", "one-click MCP for Claude / Cursor / VS Code", "Vercel", "AWS ECS"],
    "model":    ["open-core — open engine + private correctness corpus"],
    "compose":  ["x402", "pay.sh", "OpenAPI 3.x"],
}
```

---

## 🎯 Current focus

- [ ] First 10 outside-network teams running `gecko-surf` on their Nth painful API weekly
- [ ] Validate willingness-to-pay for first-call-correctness (the decider)
- [ ] The **correctness corpus** — every call teaches how to call API X right (the moat)
- [ ] Surfpool / Solana-AI-Kit integration — comprehend the chain's tools *and* the APIs around them

---

## 🌱 Open-source contributions

- **[bytedance/deer-flow](https://github.com/bytedance/deer-flow/pull/127)** — shipped the Portuguese (pt-BR) README for ByteDance's deep-research agent framework (76k★), so Brazilian devs can pick it up in their own language.
- **[solanabr/solana-ai-kit](https://github.com/solanabr/solana-ai-kit/pull/47)** — fixed `validate.sh` falsely reporting uninitialized submodules as failures.

---

## 🤝 Looking for

| Who | Why |
|-----|-----|
| **Teams shipping multi-API agents** | Bring your messiest, most painful API — let's make it first-call-correct |
| **Agent-tooling builders (Claude Code, Solana AI Kit, OKX)** | Compose Gecko's comprehension into your kit |
| **API providers with human-shaped docs** | See your surface become agent-usable, unilaterally |

---

## 💬 Let's talk

Building agents that have to call real, painful APIs? That's the whole job.

**DM me on [X](https://x.com/ernanibritto)** or **[LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)**

<div align="center">

---

*"The spec is free. The correct first call is not."*

</div>
